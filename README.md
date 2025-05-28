# Aula: Executando Script e Verificando Dados no Supabase 🚀

## 📖 Descrição  
Nesta aula, você aprenderá a executar um script TypeScript que insere registros no banco de dados Supabase e como verificar esses dados diretamente no painel do Supabase. ✅

---

## Passos para executar

### 1. Rodar o script

No terminal, execute:

```bash
npx ts-node index.ts
```

Você verá no terminal uma tabela com os registros inseridos.

### 2. Verificar no painel Supabase

- Acesse o painel do Supabase.
- Vá para **Table Editor**.
- Clique na tabela **Cliente**.
- Confirme que os três registros estão presentes. 🎉

---

## Estrutura final de arquivos

```
supabase-prisma-demo/
├─ node_modules/
├─ prisma/
│  ├─ migrations/
│  └─ schema.prisma
├─ .env
├─ index.ts
├─ package.json
└─ tsconfig.json
```
