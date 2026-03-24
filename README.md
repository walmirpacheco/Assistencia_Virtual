# 🤖 Assistência Virtual

Um assistente virtual completo para Google Colab que combina reconhecimento de voz, conversão de texto para áudio e automação de tarefas em um único ambiente.

## ✨ Funcionalidades

- 🎤 **Comandos por voz** - Fale e o assistente executa
- 🔊 **Texto para áudio** - Respostas faladas em português
- 🌐 **Automações** - Abre sites, pesquisa na Wikipedia, conta piadas
- ⌨️ **Modo texto** - Digite textos para serem falados
- 🎨 **Interface amigável** - Botões e feedback visual
- 🔄 **Multi-idioma** - Suporte a português e inglês

## 📋 Comandos Disponíveis

| Comando | Ação |
|---------|------|
| `youtube` | Abre o YouTube no navegador |
| `pesquisar [assunto]` | Pesquisa na Wikipedia |
| `piada` | Conta uma piada engraçada |
| `horas` | Informa a hora atual |
| `abrir google` | Abre o Google |
| `abrir github` | Abre o GitHub |
| `ajuda` | Mostra lista de comandos |
| `sair` | Encerra o assistente |

## 🚀 Como Usar no Colab

### Passo 1: Acesse o Google Colab

1. Abra o [Google Colab](https://colab.research.google.com/)
2. Clique em **"Novo Notebook"** ou acesse: `Arquivo > Novo notebook`

### Passo 2: Copie o Código

1. Copie todo o código do assistente (a partir de `# ============================================`)
2. Cole em uma célula do notebook
3. Execute a célula com `Shift + Enter` ou clique no botão de play

### Passo 3: Interaja com o Assistente

Após a execução, você verá:

- ✅ Mensagem de inicialização
- 📋 Menu com todos os comandos
- 🎤 Botão verde "Clique e fale"

#### Usando Comandos de Voz:

1. **Clique no botão verde** "Clique e fale"
2. **Fale claramente** seu comando quando o botão ficar vermelho
3. **Aguarde 6 segundos** (gravação automática)
4. **Ouça a resposta** e veja o resultado na tela

#### Usando Modo Texto (Alternativo):

Em uma nova célula, execute:
```python
assistant.audio_processor.text_to_speech_direct()
