<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0a0a0a,50:0d1117,100:161b22&height=200&section=header&text=Pedro%20Ferolla&fontColor=00d9ff&fontSize=60&fontAlignY=55&animation=fadeIn&stroke=00d9ff&strokeWidth=1&desc=Backend%20Developer%20%7C%20Python%20%E2%80%A2%20FastAPI%20%E2%80%A2%20SQL&descAlignY=80&descSize=16&descColor=8b949e"/>

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=2500&pause=800&color=00D9FF&center=true&vCenter=true&width=700&lines=_%3E+sistemas+que+resolvem+problemas+reais;_%3E+APIs+limpas%2C+c%C3%B3digo+que+faz+sentido;_%3E+backend+developer+em+constru%C3%A7%C3%A3o;_%3E+São+Paulo+%2F%2F+Brazil)](https://git.io/typing-svg)

</div>

<br/>

<div align="center">

```
╭──────────────────────────────────────────────────────────────╮
│                                                              │
│   $ pedro --info                                             │
│                                                              │
│   name        → Pedro Ferolla                               │
│   role        → Backend Developer (em evolução)             │
│   location    → São Paulo, BR 🇧🇷                           │
│   studying    → Análise e Des. de Sistemas                  │
│   focus       → Python · FastAPI · SQL · REST APIs          │
│   status      → Building · Learning · Shipping  ████░ 80%  │
│                                                              │
╰──────────────────────────────────────────────────────────────╯
```

</div>

---

## `// stack atual`

<div align="center">

<img src="https://skillicons.dev/icons?i=python,fastapi,postgresql,sqlite,java,git,github,vscode&theme=dark&perline=8" />

<br/><br/>

| Camada | Tecnologia | Nível |
|--------|-----------|-------|
| Linguagem principal | Python | `███████████░` 90% |
| API Framework | FastAPI | `██████████░░` 83% |
| Banco de dados | SQL / PostgreSQL | `█████████░░░` 78% |
| OOP | Python & Java | `████████░░░░` 72% |
| Versionamento | Git + GitHub | `████████░░░░` 75% |
| Containerização | Docker | `█████░░░░░░░` 48% |

</div>

---

## `// projetos em destaque`

<table>
<tr>
<td valign="top" width="50%">

### 🔐 FastAPI User Management API
> Sistema completo de gerenciamento de usuários com autenticação, rotas REST e estrutura escalável.

```python
@app.post("/users/", response_model=UserOut)
def create_user(user: UserCreate, db: Session):
    return crud.create_user(db=db, user=user)
```

**Stack:** `FastAPI` `Python` `SQLAlchemy` `REST`

[![Repo](https://img.shields.io/badge/ver%20repositório-0d1117?style=for-the-badge&logo=github&logoColor=00d9ff&labelColor=161b22)](https://github.com/phferolla/fastapi-user-management-api)

</td>
<td valign="top" width="50%">

### 🏦 Banking System OOP
> Sistema bancário orientado a objetos com operações de conta, herança e encapsulamento real.

```python
class ContaCorrente(ContaBancaria):
    def sacar(self, valor: float) -> None:
        if valor <= self.saldo:
            self.saldo -= valor
```

**Stack:** `Python` `OOP` `Classes` `Encapsulamento`

[![Repo](https://img.shields.io/badge/ver%20repositório-0d1117?style=for-the-badge&logo=github&logoColor=ffd43b&labelColor=161b22)](https://github.com/phferolla/bank-account-system-oop)

</td>
</tr>
<tr>
<td valign="top" width="50%">

### 🛒 Garimpo Secreto App
> Aplicação real com propósito de negócio — automação de processos de compra e cotações.

```bash
$ python main.py
> Carregando fornecedores...
> Gerando cotações...
> Relatório gerado ✓
```

**Stack:** `Python` `Automação` `Processo real`

[![Repo](https://img.shields.io/badge/ver%20repositório-0d1117?style=for-the-badge&logo=github&logoColor=00ff88&labelColor=161b22)](https://github.com/phferolla/garimpo-secreto-app)

</td>
<td valign="top" width="50%">

### 📚 Sistema Bancário (Projeto Final)
> Versão avançada com SQL, transações reais e arquitetura mais robusta. Evolução direta do OOP.

```sql
SELECT conta_id, saldo
FROM contas
WHERE status = 'ativa'
ORDER BY saldo DESC;
```

**Stack:** `Python` `SQL` `Arquitetura` `Lógica`

[![Repo](https://img.shields.io/badge/ver%20repositório-0d1117?style=for-the-badge&logo=github&logoColor=9d4edd&labelColor=161b22)](https://github.com/phferolla/projeto-sistema-bancario)

</td>
</tr>
</table>

---

## `// github stats`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=phferolla&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00d9ff&icon_color=00d9ff&text_color=c9d1d9&ring_color=00d9ff" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=phferolla&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00d9ff&text_color=c9d1d9&langs_count=6" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=phferolla&theme=github-dark-blue&hide_border=true&background=0d1117&ring=00d9ff&fire=00d9ff&currStreakLabel=00d9ff" />

</div>

---

## `// atividade recente`

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=phferolla&bg_color=0d1117&color=00d9ff&line=00d9ff&point=ffffff&area=true&hide_border=true&area_color=00d9ff" />

</div>

---

## `// filosofia de código`

<div align="center">

> *"Código bom não é o que impressiona — é o que funciona, qualquer um entende e é fácil de mudar."*

</div>

```python
class PedroFerolla:

    def __init__(self):
        self.nome = "Pedro Ferolla"
        self.stack = ["Python", "FastAPI", "SQL", "Git"]
        self.objetivos = ["Backend Dev", "APIs escaláveis", "Problemas reais"]
        self.status = "em evolução constante 🚀"

    def trabalhar(self) -> str:
        while True:
            self.aprender()
            self.construir()
            self.melhorar()
        # nunca para
```

---

## `// conecte-se`

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-phferolla-0d1117?style=for-the-badge&logo=github&logoColor=white&labelColor=161b22)](https://github.com/phferolla)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pedro%20Ferolla-0077b5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/phferolla)

<br/>

![Visitors](https://komarev.com/ghpvc/?username=phferolla&color=00d9ff&style=for-the-badge&label=VISITAS+AO+PERFIL)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:161b22,100:0d1117&height=100&section=footer&text=feito%20com%20Python%20%2B%20café%20%E2%98%95&fontColor=8b949e&fontSize=14&fontAlignY=65"/>

</div>
