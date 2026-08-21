# Relatório de Execução - Exercício Git

## 1. Conferência do Repositório

### Saídas dos Comandos de Conferência:

```text
1. Topologia do Histórico (git log --oneline --graph --all --decorate):
* 70d87e4 (HEAD -> main, tag: v1.0, origin/main) 27 integra guia de estilo
|\
| * 0354d44 Ev 16: Merge tipografia em guia-de-estilo
| |\
| | * 6ff790a Ev 10: Add formato datas
| | * 3a0e1aa Ev 06: Cria guia de estilo com frases
| * | 6c79f8b Ev 13: Add agenda completa
| * | 6681613 Ev 08: Cria guia de estilo com titulos
| |/
| * 224864d Ev 04: Add guia de estilo no indice
* | c53e6cb 25 integra limpeza
|\ \
| * | b179825 Ev 09: Apaga rodape
|/ /
* | 213f3ff 23 integra abertura
|\ \
| * | b037a47 20 traz main para a abertura
| |\ \
| | * | 65e7577 Ev 14: Renomeia agenda
| | * | c681ed1 Ev 05: Add item na agenda
| | * | 512fa78 Ev 03: Add agenda no indice
| |/ /
| * | 538361e 22 guia de contribuicao
| |/
* | 9c6c077 Ev 19: Merge acessibilidade em main
|\ \
| * | 37801cc Ev 18: Add info sobre
| * | d7a643b Ev 07: Add telefone rodape
| |/
* / 19857e2 Ev 11: Add subtitulo README
|/
* a488d1f Evento 02: Acrescenta ao fim do README.md
* 4062323 Ev 01: Arquivos Iniciais

2. Contagem de Commits e Merges:
- Total de Commits (git rev-list --count HEAD): 21
- Commits de Merge (git rev-list --merges --count HEAD): 5

3. Branches Restantes (git branch -a):
* main

4. Marcadores de Conflito (findstr /S /N /C:"<<<<<<<" *):
Nenhum marcador encontrado.

5. Links Relativos do Manual (findstr /S /N /C:"](docs/" *):
docs\en\README.md:2:- [Schedule](docs/agenda.md)
README.md:4:- [Sobre a mostra](docs/sobre.md)
README.md:5:- [Programação](docs/programacao.md)
README.md:6:- [Guia de estilo](docs/guia-de-estilo.md)