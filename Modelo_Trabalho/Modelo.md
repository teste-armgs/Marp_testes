---
marp: true
theme: default
class: 
  - lead
backgroundImage: url('./../if_back1.png')

paginate: true
---
 
# Teste de Estresse e Teste de Fuzz
### Prof. Dr. Valério Gutemberg
#### :pencil: Guilherme Cadete, Rafael Augusto, Alessandro Nunes, Moisés José, Samuel Lucas
#### :pencil: Disciplina de Testes de Software
:pencil2: Curso de Sistemas para Internet


---

# O que é Teste de Estresse?

Teste de estresse é um tipo de teste de software para verificar a capacidade de um sistema ou aplicação de lidar com um grande número de usuários simultâneos ou transações, a fim de determinar o desempenho sob condições de carga pesada.

---

# Por que Teste de Estresse é Importante?



- **Garantir desempenho** sob condições de pico de uso.
- Prevenir **sobrecarga** e **falhas** em produção.
- Identificar gargalos de desempenho.
- Assegurar a **satisfação do usuário** e a **estabilidade do sistema**.

---

# Introdução ao JMeter

Apache JMeter é uma ferramenta de software 100% Java, desenvolvida pela Apache Software Foundation, usada para testar o desempenho tanto de aplicativos estáticos quanto dinâmicos. Ela pode ser usada para simular cargas pesadas em um servidor, grupo de servidores, rede ou objeto para testar sua força ou para analisar o desempenho geral sob diferentes tipos de carga.

## Vejamos exemplos [1](https://jmeter.apache.org/usermanual/build-web-test-plan.html) e [2](https://www.youtube.com/watch?v=pr6h91dVuAU)



---

# Características do JMeter

- **Open source** e gratuito.
- Interface gráfica amigável.
- Capaz de testar **aplicações web** e **serviços web**.
- Suporta diversos protocolos: HTTP, HTTPS, FTP, SOAP, REST, TCP, etc.
- Permite a **simulação de múltiplos usuários** com comportamentos e cronogramas concorrentes.

---

# Como Usar o JMeter para Teste de Estresse

1. **Planeje seu teste**: Defina os objetivos, o número de usuários virtuais, duração do teste, etc.
2. **Configure o JMeter**: Crie um Plano de Teste, adicione Grupos de Usuários, configure Solicitações HTTP, adicione ouvintes para análise de resultados.
3. **Execute o teste**: Inicie o teste e monitore o desempenho em tempo real.
4. **Análise de Resultados**: Use os ouvintes para coletar e analisar os dados de desempenho.

---

# Exemplo Prático com JMeter

1. **Criação de um Plano de Teste**: Definindo o cenário de teste.
2. **Configuração de Usuários Virtuais**: Simulação de múltiplos usuários acessando simultaneamente.
3. **Definição das Solicitações HTTP**: Especificação das páginas ou recursos a serem testados.
4. **Execução e Monitoramento**: Início do teste e observação dos resultados em tempo real.
5. **Análise de Resultados**: Interpretação dos dados coletados para identificar possíveis melhorias.

---

# Resumo do teste de estresse

O teste de estresse é essencial para garantir a robustez e o desempenho de sistemas e aplicações. O Apache JMeter é uma ferramenta poderosa e flexível para realizar esses testes, permitindo simular diversas condições de uso e identificar potenciais gargalos antes que se tornem problemas em produção.

---

# O que é Teste de Fuzz

Uma técnica de teste que consiste em fornecer entradas de dados inválidas ou inesperadas para a aplicação através de aplicativos que automatizam o processo.

---

# Por que teste de fuzz é importante?

1. **Detecção de vulnerabilidades**: O fuzzing ajuda a encontrar vulnerabilidades de segurança que podem ser exploradas por atacantes.
2. **Automatização e Eficiência:**: Testes de fuzz são normalmente automatizados, permitindo que grandes volumes de dados sejam testados rapidamente sem intervenção manual.
3. **Teste de Limites e Erros de Manipulação de Entrada**: O fuzzing é eficaz para testar limites de entrada e erros de manipulação de dados que podem não ser considerados durante o desenvolvimento da aplicação.
4. **Redução de Riscos Pós-Desenvolvimento**: Reduz a chance de riscos durante a fase de produção.

---
# Ferramentas

O Teste de fuzzing pode ser feito com várias ferramentas.

1. Sulley: Framework de fuzzing feito em python.
2. AFL: Ferramenta de código aberto.
3. LibFuzzer: Ferramenta geralmente usada para testes em C e C++.
---

# Obrigado!

Dúvidas?

