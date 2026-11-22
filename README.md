# VM bootstrap encrypted releases

Encrypted bootstrap bundles for Debian and Ubuntu VMs, configured through local
Ansible playbooks. The source project and personal profile are private.

Execution requires a separately provided launch command containing the exact
archive URL, its SHA-256 and its passphrase. Verify the encrypted file before
decrypting and executing it. Never post that command or passphrase in this repository.

Release files live under `releases/<version>/`. `SHA256SUMS` describes the
ciphertext; the expected hash in the private launch command is authoritative.

