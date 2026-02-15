
# http_server.asm

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub Repo Size](https://img.shields.io/github/repo-size/sandbox-systms/http_server.asm)](https://github.com/sandbox-systms/http_server.asm)
[![Stars](https://img.shields.io/github/stars/sandbox-systms/http_server.asm)](https://github.com/sandbox-systms/http_server.asm/stargazers)
[![Forks](https://img.shields.io/github/forks/sandbox-systms/http_server.asm)](https://github.com/sandbox-systms/http_server.asm/network/members)
[![Issues](https://img.shields.io/github/issues/sandbox-systms/http_server.asm)](https://github.com/sandbox-systms/http_server.asm/issues)

## Overview

**http_server.asm** é um servidor HTTP minimalista escrito em Assembly para **Linux x86/x86_64**. O projeto demonstra como montar um servidor básico usando apenas chamadas de sistema (syscalls), sem dependências externas, e serve como estudo de baixo-nível sobre redes e programação em Assembly para Linux.

## Features

- Servidor HTTP básico em Assembly.
- Suporte a conexões TCP usando syscalls de socket do Linux.
- Estrutura simples e enxuta, ideal para aprendizado de redes e syscalls.
- Compilação com `nasm` e linkagem direta com o `ld`.

## Requirements

- Linux com arquitetura **x86 ou x86_64**
- NASM (Netwide Assembler)
- GNU ld (link editor)
- Ferramentas comuns de desenvolvimento (`make`, `gcc`, etc.)
