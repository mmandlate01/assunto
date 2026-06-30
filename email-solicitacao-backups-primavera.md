# Modelo de Email — Solicitação de Backups da Base de Dados PRIMAVERA (encerramento do serviço na cloud)

> Substitua os campos entre `[...]` pelos dados reais antes de enviar.
> Aplica-se ao ERP **PRIMAVERA** alojado em cloud/servidor gerido por terceiros.

---

**Para:** [suporte@fornecedor.com / parceiro.primavera@empresa.com]
**Cc:** [responsavel.interno@empresa.com]
**Assunto:** Solicitação de backups da base de dados PRIMAVERA — empresa [Nome/Código] (encerramento do serviço)

---

Exmos. Senhores,

No seguimento da decisão de **descontinuar o serviço de alojamento em cloud** do
nosso ERP **PRIMAVERA**, vimos solicitar formalmente a **entrega da cópia de
segurança completa das bases de dados e respetivos ficheiros**, antes do
encerramento e eliminação definitiva do ambiente.

Agradecemos que a entrega contemple os seguintes elementos:

1. **Bases de dados SQL Server (ficheiros `.bak`)**
   - Base de dados da **empresa**: `[PRIEMP... / nome da BD]`;
   - Base de dados de **configuração / administrador**: `[PRIPDA / PRIMAVERA Configuração]`;
   - Quaisquer outras bases associadas (ex.: empresas adicionais, anos anteriores,
     históricos arquivados).
   - Backup **full** (completo), gerado preferencialmente com `BACKUP DATABASE`
     do SQL Server, e indicação da **versão do SQL Server** utilizada.

2. **Versão da aplicação**
   - Indicação da **versão e build do PRIMAVERA** em utilização (ex.: v10, v9.x),
     para garantir compatibilidade no restauro;
   - Lista dos **módulos** instalados/licenciados (ex.: Contabilidade, Gestão
     Comercial, Recursos Humanos, etc.).

3. **Ficheiros e personalizações**
   - Pasta de **anexos/documentos digitalizados** associados aos registos (ex.:
     faturas, ged/documentos);
   - **Mapas, listagens e templates** personalizados (CrystalReports / mapas
     PRIMAVERA);
   - Configurações específicas, integrações e dados de licenciamento, caso aplicável.

4. **Método de entrega**
   - [Download seguro via link temporário / transferência SFTP / suporte físico
     encriptado], conforme vos for mais conveniente;
   - Entrega **encriptada**, com a chave/password transmitida por canal separado.

5. **Integridade e validação**
   - Inclusão de **somas de verificação (checksums/hashes)** dos ficheiros `.bak`;
   - Confirmação de que os backups foram gerados **sem erros** e que permitem o
     restauro completo.

6. **Prazos e retenção**
   - Solicitamos a confirmação de que as bases de dados e ficheiros **não serão
     eliminados** até concluirmos a validação (restauro de teste) dos backups;
   - Agradecemos a entrega até **[data limite]**.

Após a receção e validação dos backups (restauro de teste bem-sucedido),
confirmaremos por escrito a autorização para procederem à **eliminação definitiva
dos dados** e ao encerramento do ambiente, nos termos do contrato e da legislação
de proteção de dados aplicável.

Para qualquer esclarecimento, o ponto de contacto da nossa parte é:

- **Nome:** [Nome do responsável]
- **Cargo:** [Cargo]
- **Email / Telefone:** [contacto]

Com os melhores cumprimentos,

**[O seu nome]**
**[Cargo]**
**[Empresa]**
**[Contactos]**

---

## Versão curta

**Assunto:** Pedido de backup da base de dados PRIMAVERA — empresa [Código]

Exmos. Senhores,

Tendo decidido descontinuar o alojamento em cloud do nosso ERP **PRIMAVERA**,
solicitamos a entrega da **cópia de segurança completa (`.bak`)** das bases de
dados da **empresa** e de **configuração**, juntamente com os **anexos/documentos**
e **mapas personalizados**, em ficheiro encriptado e com verificação de integridade.

Agradecemos que indiquem a **versão do PRIMAVERA e do SQL Server** e que **não
eliminem** os dados até confirmarmos a validação dos backups. Pedimos ainda
indicação do prazo de entrega.

Com os melhores cumprimentos,
**[O seu nome] — [Empresa]**
