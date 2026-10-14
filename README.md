# Murilo Mota

**Desenvolvedor backend em formação** — Java · Spring Boot · PostgreSQL

Estudo no 3º ano do Ensino Médio integrado ao técnico em Jogos Digitais na
**ETEC Carmelina Barbosa**, em Junqueirópolis (SP). Escrevo código desde setembro de 2025 e
hoje concentro os estudos em backend: APIs REST, modelagem de banco de dados e o que separa
código que funciona de código que outra pessoa consegue manter.

**Busco uma oportunidade de estágio em desenvolvimento de software.**

---

## Projetos em destaque

### [Sorveteria-API](https://github.com/omurilomota/Sorveteria-API) · Java 21 · Spring Boot

API REST para uma operação de sorveteria: catálogo, clientes e pedidos com cálculo de total
e transição de status validada.

- 1.384 linhas de Java e 22 endpoints distribuídos em 4 controllers
- Arquitetura Controller → Service → Repository, com DTOs isolando o contrato da API das
  entidades JPA
- Senhas armazenadas com hash BCrypt
- Spring Security configurado, mas a autenticação por JWT **ainda não está implementada**:
  o filtro é uma classe vazia e os endpoints estão liberados. Consta como próximo passo no
  [ROADMAP](https://github.com/omurilomota/Sorveteria-API/blob/master/ROADMAP.md)
- Tratamento global de exceções, com respostas de erro padronizadas e documentação OpenAPI

### [Olho Eletrônico](https://github.com/omurilomota/Olho-Eletronico) · React 19 · TypeScript · three.js

Sistema web de simulação e monitoramento da Copa de 2026, com análise de impedimento em 3D e
uma central de comando com gêmeos digitais.

- 116 commits · 9 arquivos de teste + 3 suítes end-to-end (Vitest e Playwright)
- Interface em português, inglês e espanhol
- Multiplayer em tempo real com Supabase

### [Estacionamento Autônomo](https://github.com/omurilomota/estacionamento-automatico-godot) · Godot 4 · GDScript

Simulação em que o carro não segue um script fixo: ele lê o ambiente pelos sensores e decide
quando procurar vaga, desviar e estacionar.

- 152 commits · projeto em equipe de 3 pessoas, com responsabilidades divididas por arquivo
- Planejamento de rota com A* sobre grade de ocupação
- Máquina de estados com recuperação de colisão

### [ChicPets](https://github.com/omurilomota/petshop-Chic) · React · TypeScript · Tailwind CSS

Landing page de um petshop e estética animal de Junqueirópolis, com o conteúdo do negócio
centralizado em um único arquivo de configuração e verificação automática a cada push.

---

## Tecnologias

**Backend** — Java 21 · Spring Boot · Spring Security (JWT) · JPA / Hibernate ·
Bean Validation · OpenAPI · Maven · JUnit

**Web** — TypeScript · React · Vite · Tailwind CSS · Zustand · three.js · Vitest · Playwright

**Jogos** — C# · Godot 4 · GDScript · Unity · A* (pathfinding) · máquinas de estado

**Dados e ferramentas** — PostgreSQL · SQL · Git · GitHub Actions · Linux

---

## Contato

- **E-mail:** murilohenriquemota935@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/murilo-henrique-622354358/
