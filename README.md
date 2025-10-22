<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Perfil</title>
    <style>
        /* 1. Configurações Globais */
        body, html {
            height: 100%; /* Faz o corpo ocupar a altura toda da tela */
            margin: 0;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: #f0f2f5; /* Um fundo cinza claro */
        }

        /* 2. O Contêiner Flex para Centralizar */
        body {
            display: flex;
            justify-content: center; /* Centraliza horizontalmente */
            align-items: center;    /* Centraliza verticalmente */
        }

        /* 3. O Cartão de Perfil */
        .profile-card {
            background-color: #ffffff;
            padding: 2rem 3rem; /* Espaçamento interno */
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
            max-width: 500px; /* Largura máxima do cartão */
            width: 90%; /* Responsivo para telas pequenas */
        }

        /* 4. Estilo do Título e dos Tópicos */
        .profile-card h1 {
            text-align: center;
            color: #333;
            margin-top: 0;
        }

        .profile-card ul {
            list-style-type: none; /* Remove as bolinhas da lista */
            padding: 0;
        }

        .profile-card li {
            font-size: 1.1rem;
            line-height: 1.6; /* Altura da linha para melhor leitura */
            color: #555;
            margin-bottom: 1rem; /* Espaço entre os tópicos */
        }
        
        /* Adiciona um emoji antes de cada tópico */
        .profile-card li::before {
            content: '🔹'; /* Você pode trocar por '✔️', '💻', etc. */
            margin-right: 10px;
        }

    </style>
</head>
<body>

    <div class="profile-card">
        <h1>Sobre Mim</h1>
        
        <ul>
            <li>Hoje trabalho com ReactJS e NodeJS.</li>
            <li>Tenho um pouco de experiência com Python também.</li>
            <li>Meus pronomes são ele/dele.</li>
            <li>Gosto de fazer projetinhos de forma esporádica.</li>
        </ul>
    </div>

</body>
</html>

<!--
**veniciusgomes/veniciusgomes** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
