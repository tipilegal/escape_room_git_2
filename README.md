# 🧩 Escape Room Git 2 — O Histórico Corrompido

Você acaba de entrar na empresa **BlackVault Systems**.

O sistema parou de funcionar depois que o histórico do Git foi completamente bagunçado.
O desenvolvedor anterior deixou apenas a seguinte mensagem:

> "A frase está no histórico.
> Mas o histórico foi corrompido.
> Commits fora de ordem, arquivos errados, branches esquecidas…
>
> Coloque tudo no lugar.
> Remova o que não deveria existir.
> Organize os commits.
>
> Quando a frase estiver correta… o sistema volta."

---

## 🎯 Objetivo

O histórico atual contém vários commits com pistas dentro da pasta `pistas/` ou espalhados pelo projeto ou em arquivos nomeados de forma errada.

Cada pista contém uma palavra.

Os commits estão fora de ordem e existem commits errados misturados.

Seu objetivo é:

- remover commits desnecessários
- recuperar arquivos perdidos
- usar commits de outras branches
- organizar os commits na ordem correta
- formar uma frase com as palavras
- Deixar a branch main com o histórico limpo

Nem todos os commits devem permanecer no histórico final.

---

## 🧩 Desafio principal

Você deve reorganizar o histórico para que:

- apenas os commits corretos permaneçam
- os commits com pistas fiquem na ordem correta
- a ordem dos commits forme uma frase

Cada commit com pista contém uma palavra.

A ordem correta dos commits deve formar uma frase válida.


A main deve ter um histórico limpo contendo apenas:

- README.md
- config.js
- src/
- arquivos corretos da pasta pistas

Os commits devem estar na ordem correta formando a frase.

O último commit deve ser:

sistema restaurado: <FRASE>


---

## 🏁 Regras

❌ Não apagar o repositório
❌ Não criar outro repositório
❌ Não copiar arquivos sem usar git

✔ Pode usar rebase
✔ Pode usar revert
✔ Pode usar cherry-pick
✔ Pode usar branch
✔ Pode usar merge
✔ Pode usar tag
✔ Pode usar checkout
✔ ...

---