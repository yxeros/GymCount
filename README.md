# GymCount

App móvel de séries, repetições e timers. Não precisa instalar pacotes.

## Abrir no computador

No PowerShell, dentro desta pasta, execute:

```powershell
py -m http.server 8000
```

Depois abra `http://localhost:8000` no navegador.

## Abrir no celular pela rede local

Com o computador e o celular no mesmo Wi-Fi, inicie o servidor aceitando conexões da rede:

```powershell
py -m http.server 8000 --bind 0.0.0.0
```

No celular, abra `http://IP-DO-COMPUTADOR:8000`. Para instalar na tela inicial e usar offline como app, publique os mesmos arquivos em um endereço HTTPS e use a opção “Adicionar à tela inicial” do navegador.

## Dados

Exercícios, contadores e progresso ficam salvos no armazenamento local do navegador. Eles não sincronizam entre aparelhos; limpar os dados do navegador também apaga o que foi salvo.
