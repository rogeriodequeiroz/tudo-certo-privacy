# Política de Privacidade — Tudo Certo

_Última atualização: 23 de novembro de 2026 (versão 1.0)._

O **Tudo Certo** ("o aplicativo") é um aplicativo para Android de profissionais de beleza e
estética: calcula o preço dos serviços, monta tabelas de preço e propagandas e envia cobranças
para a maquininha Mercado Pago da profissional. Ele é desenvolvido pela **Solutions Tecnologia**
(responsável: **Rogerio Queiroz**), que responde por esta política. Ela explica quais dados o
aplicativo usa, onde eles ficam, com quem são trocados e por quê.

**Resumo:**
- Você entra com a sua **conta Google**. Usamos o nome, o e-mail e um identificador da conta só
  para manter o seu acesso e proteger as suas cobranças.
- Os dados das suas **clientes** (nomes, telefones, fotos e autorizações), o seu catálogo e o seu
  histórico de vendas ficam **só no seu celular, cifrados**. Eles não vão para os nossos servidores.
- Para cobrar na maquininha, o nosso servidor, **no Brasil (São Paulo)**, guarda os dados de cada
  cobrança — valor, forma de pagamento, parcelas, maquininha e situação —, **sem** nome de cliente e
  **sem** descrição do serviço.
- **Não há** anúncios, análise de uso (analytics) nem venda de dados.

## 1. Quem trata os dados
- **Dados da sua conta e das suas cobranças:** a Solutions Tecnologia é a controladora.
- **Dados das suas clientes:** você, profissional, é a controladora (Lei Geral de Proteção de
  Dados — LGPD). Esses dados ficam no seu celular. A Solutions Tecnologia só trata, como operadora,
  o que passa pelo servidor numa cobrança (que não inclui o nome da cliente) e **nunca** usa dados
  das suas clientes para fins próprios.

## 2. Sua conta
- **Login com Google** (Firebase Authentication, do Google): ao entrar, o Google nos fornece o seu
  **nome**, **e-mail**, **foto do perfil** e um **identificador** da conta. Usamos esses dados para
  identificar você e proteger o acesso às suas cobranças. Eles são guardados pelo Google, em data
  centers nos **Estados Unidos** (veja a seção 11).
- **Uma conta por celular:** os dados do aparelho ficam ligados à primeira conta que entrar. Outra
  conta Google não vê as vendas nem as clientes de quem entrou antes.
- **Verificação do aplicativo** (Firebase App Check com o Google Play Integrity): confere que os
  pedidos de cobrança vêm do aplicativo original da Google Play. O Google avalia a integridade do
  aparelho e do aplicativo; nós recebemos só um código de verificação, sem dados do aparelho.

## 3. O que fica só no seu celular
- **Clientes** (nome, telefone, fotos de antes e depois e autorizações de uso de imagem),
  **produtos, serviços, preços e histórico de vendas:** no banco de dados do aplicativo, **cifrado**.
- **Chave do Gemini** (se você usar imagens com IA): guardada cifrada no aparelho. Ela nunca vai
  para os nossos servidores nem para as cópias de segurança.
- **Cópias de segurança:**
  - **backup automático do Android**, na sua conta Google: inclui só o banco de dados do
    aplicativo, e só quando o Android consegue cifrá-lo de ponta a ponta (com o bloqueio de tela do
    celular) — nem nós nem o Google conseguimos ler. A chave do banco fica guardada pelo serviço Block
    Store do Google, para o aplicativo reabrir os dados num celular novo;
  - **cópia manual**, protegida por uma senha que só você conhece, salva onde você escolher.
- Desinstalar o aplicativo apaga os dados do celular. Os backups da sua conta Google seguem as
  regras do Google.

## 4. Cobranças na maquininha (Mercado Pago)
- **Conectar a sua conta Mercado Pago:** a autorização é feita na página do próprio Mercado Pago.
  O nosso servidor guarda os códigos de acesso dessa conta **cifrados** e o apelido e o e-mail da
  conta Mercado Pago, para mostrar a você para qual conta vai o dinheiro.
- **Cada cobrança:** o servidor guarda valor, forma de pagamento, parcelas, quem paga os juros, a
  maquininha, a situação, os códigos da ordem no Mercado Pago e um registro técnico das etapas — sem
  nome de cliente e sem descrição do serviço.
- **O Mercado Pago** recebe o valor, a maquininha, a forma de pagamento e um código aleatório da
  cobrança, e processa o pagamento segundo a política dele
  (<https://www.mercadopago.com.br/privacidade>).
- O aplicativo **não recebe** dados do cartão da sua cliente: o pagamento acontece na maquininha.
- **Onde fica:** Google Cloud, região de **São Paulo, Brasil**.
- **Avisos no celular:** para avisar quando uma cobrança muda (por exemplo, quando é paga), o
  aplicativo pode registrar um identificador de notificação do Firebase Cloud Messaging. O aviso
  leva só o código da cobrança — nenhum valor, nome ou situação.

## 5. Imagens com inteligência artificial (Google Gemini)
- Para criar tabelas de preço e propagandas, você usa a **sua própria chave** do Google Gemini,
  contratada por você com o Google. O pedido (textos, preços, logotipo e imagens que você escolher)
  vai **direto do seu celular ao Google**, segundo os termos que você aceitou com ele. Nós não
  recebemos nem guardamos esses pedidos.
- **Fotos de clientes não são enviadas à IA:** a montagem com essas fotos é feita no próprio celular.
- Mostramos a você as imagens geradas para conferir os preços antes de usar.

## 6. Assinatura
A assinatura é cobrada pela **Google Play**; o aplicativo não recebe dados de pagamento. Para
controlar a assinatura usamos o **RevenueCat**, que recebe só um identificador interno aleatório e
os dados da compra fornecidos pela Play (política: <https://www.revenuecat.com/privacy>).

## 7. O que não fazemos
- Não exibimos anúncios.
- Não usamos análise de uso (analytics) nem rastreamento.
- Não vendemos nem compartilhamos dados para marketing.
- Não usamos dados das suas clientes para fins próprios (vitrine, bases de dados, treino de IA).

## 8. Bases legais (LGPD)
- **Execução do contrato** com você: conta, cobranças, assinatura.
- **Legítimo interesse e segurança:** verificação do aplicativo e registro técnico das cobranças
  (para evitar fraudes, cobranças em dobro e perdas).
- **Cumprimento de obrigação legal:** registros que a lei mande guardar.
- **Consentimento das suas clientes** para o uso das fotos delas: colhido por você, no aplicativo,
  cliente a cliente.

## 9. Por quanto tempo guardamos
- **Conta e cobranças:** enquanto a sua conta existir.
- **Notificações técnicas do Mercado Pago:** apagadas até 90 dias depois de processadas.
- **Pedidos de conexão com o Mercado Pago não concluídos:** apagados em até 1 dia.
- **Exclusão da conta:** peça pelo e-mail da seção 13 (e, quando disponível, no próprio
  aplicativo). Apagamos a conta e os dados do servidor em até 30 dias, salvo o que a lei obrigar a
  guardar. Os dados do celular são apagados ao desinstalar o aplicativo ou limpar os dados dele.

## 10. Seus direitos (LGPD, art. 18)
Você pode pedir confirmação e acesso aos seus dados, correção, anonimização, portabilidade,
eliminação, informação sobre com quem compartilhamos e revogação de consentimentos, pelo contato da
seção 13. Pedidos sobre dados das clientes devem ser feitos à profissional, que é a controladora
desses dados — e nós a ajudamos a atender.

## 11. Transferência internacional
O login (Firebase Authentication, do Google) e o controle de assinatura (RevenueCat) guardam dados
nos **Estados Unidos**, com as garantias contratuais desses fornecedores. Os dados das cobranças
ficam no Brasil.

## 12. Segurança
Conexões com HTTPS (TLS); dados do celular cifrados; códigos de acesso do Mercado Pago cifrados no
servidor; o servidor só atende quem entrou na conta, pelo aplicativo verificado, e cada conta só
enxerga os próprios dados.

## 13. Contato e encarregado
**Solutions Tecnologia** — responsável e encarregado pelo tratamento de dados: **Rogerio Queiroz**.
E-mail: **rogerio.de.queiroz.3l@gmail.com**.

## 14. Crianças
O aplicativo é para profissionais maiores de 18 anos e não é direcionado a crianças ou adolescentes.

## 15. Alterações
Mudanças nesta política serão publicadas nesta mesma URL, com a data atualizada. Mudanças
importantes também serão avisadas no aplicativo.
