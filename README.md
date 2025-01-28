# DETALHE-VISTORIAS (NAME)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Detalhe Vistorias | Vistorias Imobiliárias</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&family=Open+Sans:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Reset CSS */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Open Sans', sans-serif;
            line-height: 1.6;
        }

        /* Cores */
        :root {
            --azul: #2A3B4D;
            --cinza: #6C757D;
            --branco: #FFFFFF;
        }

        /* Header/Hero Section */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1560518883-ce09059eeffa');
            background-size: cover;
            background-position: center;
            color: var(--branco);
            text-align: center;
            padding: 120px 20px;
        }

        .hero h1 {
            font-size: 2.5em;
            margin-bottom: 20px;
            font-family: 'Roboto', sans-serif;
        }

        .hero p {
            font-size: 1.2em;
            margin-bottom: 30px;
        }

        /* Botões */
        .btn {
            padding: 12px 30px;
            border-radius: 5px;
            text-decoration: none;
            margin: 10px;
            display: inline-block;
        }

        .btn-primary {
            background-color: var(--azul);
            color: var(--branco);
        }

        .btn-secondary {
            background-color: var(--cinza);
            color: var(--branco);
        }

        /* Seções comuns */
        section {
            padding: 60px 20px;
            text-align: center;
        }

        .section-title {
            color: var(--azul);
            margin-bottom: 40px;
            font-family: 'Roboto', sans-serif;
        }

        /* Serviços */
        .servicos-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .servico-card {
            padding: 20px;
            border: 1px solid #e0e0e0;
            border-radius: 8px;
        }

        /* Depoimentos */
        .depoimentos-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            max-width: 1000px;
            margin: 0 auto;
        }

        .depoimento-card {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            text-align: left;
        }

        /* Formulário */
        .contato-form {
            max-width: 600px;
            margin: 0 auto;
        }

        input, select, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 4px;
        }

        /* Footer */
        footer {
            background-color: var(--azul);
            color: var(--branco);
            padding: 40px 20px;
            text-align: center;
        }

        .footer-content {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .footer-section {
            margin: 20px;
        }

        /* Responsivo */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2em;
            }
        }
    </style>
</head>
<body>
    <!-- Hero Section -->
    <header class="hero">
        <h1>Vistorias Imobiliárias Precisas e Confiáveis</h1>
        <p>Garanta a segurança e o valor do seu imóvel com um serviço detalhado e profissional.</p>
        <a href="#contato" class="btn btn-primary">Solicite uma Vistoria Agora</a>
        <a href="#servicos" class="btn btn-secondary">Saiba Mais</a>
    </header>

    <!-- Sobre Nós -->
    <section id="sobre">
        <h2 class="section-title">Quem Somos</h2>
        <p>Na <strong>Detalhe Vistorias</strong>, oferecemos serviços especializados em vistorias imobiliárias, ajudando proprietários, compradores e corretores a tomar decisões informadas. Nossa equipe é formada por profissionais experientes e capacitados, garantindo um trabalho minucioso e transparente.</p>
    </section>

    <!-- Serviços -->
    <section id="servicos" style="background-color: #f8f9fa;">
        <h2 class="section-title">Nossos Serviços</h2>
        <div class="servicos-grid">
            <div class="servico-card">
                <h3>Vistoria Pré-Compra</h3>
                <p>Análise detalhada para garantir seu investimento</p>
            </div>
            <!-- Repetir para outros serviços -->
        </div>
        <a href="#contato" class="btn btn-primary">Conheça Todos os Serviços</a>
    </section>

    <!-- Diferenciais -->
    <section id="diferenciais">
        <h2 class="section-title">Por Que Escolher a Detalhe?</h2>
        <ul style="list-style: none; max-width: 600px; margin: 0 auto;">
            <li style="margin: 15px 0;">✓ Equipe técnica especializada</li>
            <!-- Repetir para outros diferenciais -->
        </ul>
    </section>

    <!-- Depoimentos -->
    <section id="depoimentos" style="background-color: #f8f9fa;">
        <h2 class="section-title">O Que Nossos Clientes Dizem</h2>
        <div class="depoimentos-grid">
            <div class="depoimento-card">
                <p>"Profissionais extremamente competentes!" – Maria S.</p>
            </div>
            <!-- Repetir para outros depoimentos -->
        </div>
    </section>

    <!-- Contato -->
    <section id="contato">
        <h2 class="section-title">Entre em Contato</h2>
        <form class="contato-form">
            <input type="text" placeholder="Nome" required>
            <input type="email" placeholder="E-mail" required>
            <input type="tel" placeholder="Telefone">
            <select>
                <option>Selecione o Serviço</option>
                <option>Vistoria Pré-Compra</option>
                <!-- Outras opções -->
            </select>
            <textarea placeholder="Mensagem" rows="5"></textarea>
            <button type="submit" class="btn btn-primary">Enviar Mensagem</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <div class="footer-section">
                <h3>Contato</h3>
                <p>Rua Exemplo, 123</p>
                <p>(11) 99999-9999</p>
                <p>contato@detalhevistorias.com</p>
            </div>
            <div class="footer-section">
                <h3>Redes Sociais</h3>
                <!-- Adicionar ícones aqui -->
            </div>
        </div>
        <p style="margin-top: 20px;">© 2023 Detalhe Vistorias</p>
    </footer>
</body>
</html>
