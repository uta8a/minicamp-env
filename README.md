# minicamp env
- ansibleを用いて環境構築
- RDP前提(バイナリエディタ: ghexを使うため)
- ディレクトリ構造
```
.
├── inventory # vm:minicamp-hiroshimaに対して行う
├── playbook.yml # Userはここのvarsで指定
└── tasks
    ├── checksec.yml
    └── rp.yml
```
- インストールするもの一覧
```
- ltrace
- strace
- vim
- gdb
- git
- file
- curl
- wget
- binutils
- libssl-dev
- build-essential
- netcat
- nasm
- python3
- python3-pip
- python3-dev
- ghex
- radare2
- docker.io
- checksec
- rp++
- Rust
- VSCode
```