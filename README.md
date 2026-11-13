# Sequência Quiz

Quiz interativo para treinar a inspeção manual de cromatogramas Sanger e distinguir mutações reais de artefatos em sequências de arbovírus.

**Acesse:** https://nagualcode.github.io/sequencia-quiz/

## Como jogar

1. Abra o quiz no navegador e selecione **Começar**.
2. Compare a sequência de referência com as leituras forward e reverse.
3. Inspecione os picos, a qualidade Phred e o contexto antes de escolher um veredito.
4. Use **Dica** e o **Guia rápido de inspeção** quando precisar.

O quiz apresenta desafios gerados no navegador, com cromatogramas simulados para fins didáticos. Não é necessário instalar nada: o site é composto por um único arquivo HTML.

## Executar localmente

Abra `index.html` diretamente no navegador ou inicie um servidor HTTP na pasta do projeto, por exemplo:

```sh
python3 -m http.server 8000
```

Em seguida, acesse http://localhost:8000.

## Publicação

O site é publicado pelo GitHub Pages a partir da branch `main`.

Material didático da Turma de Sequenciamento Genômico para Vigilância de Arbovírus — Fiocruz / Instituto Oswaldo Cruz, Pós-graduação em Medicina Tropical.
