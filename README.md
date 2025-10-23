  TaskMaster Mobile – Relatório de Pré-Lançamento

  Seção 1 – Requisitos Técnicos e Políticas

  Ícones e Vídeos
Google Play
- Resolução mínima: 512 × 512 px  
- Formato: PNG  
- Tamanho máximo: até 1024 kB

App Store
- Resolução mínima: 1024 × 1024 px  
- Formato: PNG (sem transparência)

Diferença principal:  
A App Store exige ícones de maior resolução e não permite transparência.  
Além disso, os vídeos promocionais seguem formatos e proporções específicas em cada loja (Play Store usa vídeos do YouTube, App Store usa vídeos curtos diretamente hospedados).

---


Políticas e Permissões
- O Google Play rejeita aplicativos que solicitam permissões não essenciais para sua funcionalidade principal.  
- As permissões devem seguir o princípio da necessidade mínima, garantindo a privacidade e segurança do usuário.  
- A Política de Privacidade deve estar publicada e acessível no aplicativo e na página da store, descrevendo:
  - Quais dados são coletados.
  - Como são armazenados e utilizados.
  - Com quem podem ser compartilhados.

Importância:  
As políticas claras aumentam a transparência e evitam rejeição durante a revisão.

---

Certificados
Android (Keystore)
- Utiliza um arquivo keystore para assinar digitalmente o APK/AAB.  
- Garante autenticidade e integridade do app nas atualizações.

iOS (Apple Developer)
- Requer certificados emitidos pela conta de desenvolvedor da Apple.  
- O app é assinado e validado via provisioning profile, garantindo segurança no ecossistema da App Store.

Diferença:  
No Android, o desenvolvedor controla a chave; no iOS, a assinatura depende da validação pela Apple.

---

 Seção 2 – Recursos Visuais e Qualidade
Briefing de Screenshots
Recomendações:
- Use as principais telas do aplicativo (ex: login, dashboard, tarefa concluída).  
- Mostre funcionalidades centrais de forma limpa e realista.  
- Utilize simulações de dispositivos reais (mockups oficiais Android e iPhone).  
- Siga diretrizes das lojas:
  - Google Play: foco em cores e contraste.
  - App Store: foco em estética e clareza.

---

 Testes Beta
Ferramentas:
- Android → Firebase Test Lab  
- iOS → TestFlight

Essas plataformas permitem testar o app em dispositivos reais, coletar feedback de usuários e identificar falhas antes da publicação oficial.

---

 Debugging e Testes de Regressão
Importância:  
- Após corrigir um erro crítico, é essencial executar testes de regressão para garantir que a correção não causou novos problemas.  
- Mantém a estabilidade e qualidade do aplicativo antes do envio às stores.

---

Pesquisa Complementar
Ao elaborar o plano de publicação:
- Analise os critérios de aprovação de cada loja.  
- Avalie os motivos comuns de rejeição (permissões incorretas, política ausente, ícones fora do padrão).  
- Crie um checklist de qualidade antes do envio.

---

 Reflexão
Durante o processo, a curiosidadeimpulsiona a exploração de melhores práticas e ferramentas, enquanto a motivação mantém o foco em entregar um produto final de alta qualidade.  
Essas atitudes são cruciais para evitar erros simples e garantir que o aplicativo seja aprovado sem rejeições nas stores.

---

 Entrega: Semana 22  
 Responsável: Ezequiel da Cruz
 Repositório: https://github.com/Ezequiel755/Readme-Mobile/new/main?readme=1
