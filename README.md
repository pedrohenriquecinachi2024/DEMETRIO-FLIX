# DEMETRIO-FLIX
/* Estilos gerais */
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #141414;
    color: #fff;
}

/* Cabeçalho */
header {
    background-color: #e50914;
    padding: 20px;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.5em;
    color: #fff;
}

/* Seção de filmes */
.filmes-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    padding: 20px;
}

.filme-card {
    background-color: #1c1c1c;
    border-radius: 8px;
    overflow: hidden;
    transition: transform 0.3s;
}

.filme-card:hover {
    transform: scale(1.05);
}

.filme-card img {
    width: 100%;
    height: auto;
    display: block;
}

.filme-card h3 {
    font-size: 1.2em;
    margin: 10px;
    color: #e50914;
}

.filme-card p {
    font-size: 0.9em;
    margin: 10px;
    color: #b3b3b3;
}

/* Rodapé */
footer {
    background-color: #1c1c1c;
    text-align: center;
    padding: 20px;
    color: #b3b3b3;
}

footer p {
    margin: 0;
    font-size: 0.9em;
}

/* Links */
a {
    color: #e50914;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}
