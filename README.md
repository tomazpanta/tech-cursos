# 📱 Tech Cursos

Aplicativo mobile desenvolvido em **React Native** para listagem de cursos de tecnologia. O app está integrado ao **Firebase Realtime Database** e utiliza variáveis de ambiente (.env) para proteger informações sensíveis.

---

## 🧠 Objetivo do Projeto

Esse projeto foi desenvolvido como parte da disciplina de Desenvolvimento Mobile, com o objetivo de aplicar conceitos de:

- Componentização com React Native
- Navegação entre telas
- Consumo de dados do Firebase
- Organização de pastas
- Boas práticas com variáveis de ambiente (.env)

---

## 🚀 Funcionalidades até 10/04

- [x] Tela inicial (Home)
- [x] Listagem de cursos (dados vindos do Firebase)
- [x] Estrutura modular (screens, services, components)
- [x] Integração com Firebase Realtime Database
- [x] Uso de variáveis de ambiente com `.env`

---

## 📸 Prints do App

### 🏠 Tela Home

<img width="364" alt="image" src="https://github.com/user-attachments/assets/022f0e59-a513-43d5-9b35-0f602c13525b" />


### 📚 Listagem de Cursos
<img width="361" alt="image" src="https://github.com/user-attachments/assets/a4c974ba-87ab-4316-8801-278639c73ea8" />

//Possível erro de DB para ser resolvido.


---

## 🔐 Firebase com .env

### 📁 Exemplo de arquivo `.env`

FIREBASE_API_KEY=your_api_key
FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
FIREBASE_DATABASE_URL=https://your_project.firebaseio.com
FIREBASE_PROJECT_ID=your_project_id
FIREBASE_STORAGE_BUCKET=your_project.appspot.com
FIREBASE_MESSAGING_SENDER_ID=your_sender_id
FIREBASE_APP_ID=your_app_id


Foi utilizado o .env para que não vaze as informações do Firebase do usuário então o arquivo .env está no gitignore para que não aconteça problema algum de vazamento de dados.
