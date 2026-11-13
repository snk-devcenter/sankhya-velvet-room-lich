# Velvet Room para o lich

Extensão do [lich](https://github.com/lichdotdev/lich) para gerenciar as bases locais do Sankhya: o banco em Docker, o Wildfly de cada base, os logs, os módulos e o MCP Sankhya Schema, numa tela com o visual nativo do lich.

Este repositório só publica os pacotes da extensão. A TUI e a CLI ficam em [sankhya-velvet-room-releases](https://github.com/snk-devcenter/sankhya-velvet-room-releases).

## Instalação

Requer o lich 0.89.0 ou mais novo e o Docker instalado.

1. No lich, abra **Settings → Extensions** e escolha instalar pelo GitHub.
2. Cole `https://github.com/snk-devcenter/sankhya-velvet-room-lich`.
3. Confirme. O lich baixa a última release para o seu sistema, confere o SHA-256 e inicia a extensão.

A tela **Bases locais** aparece na barra de cima do lich.

## Atualização

O lich não atualiza uma extensão instalada: remova a Velvet Room em **Settings → Extensions** e instale de novo pela mesma URL. Os dados da extensão são mantidos.

## Pacotes

Cada release traz `velvet-room_<os>_<arch>.tar.gz` para Linux e Windows (amd64 e arm64), com o `manifest.json` e o executável, e o `checksums.txt`.
