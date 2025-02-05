# 🍱 점심 메뉴 추천 웹 애플리케이션

이 웹 애플리케이션은 사용자가 입력한 내용을 바탕으로 점심 메뉴를 추천해주는 서비스입니다. 사용자는 모델을 선택하고 메시지를 입력하여, 추천된 점심 메뉴를 확인할 수 있습니다. 추천된 메뉴는 "Gemini"와 "DeepSeek" 두 가지 모델을 통해 제공됩니다. 🤖🍽️

## 주요 기능 ✨

- **모델 선택**: "Gemini" 또는 "DeepSeek" 모델을 선택하여 추천을 받을 수 있습니다. 🤖🔮
- **메시지 입력**: 텍스트 영역에 입력한 내용을 바탕으로 점심 메뉴 추천이 이루어집니다. 📝
- **추천 메뉴 표시**: 선택한 모델에 따라 추천된 점심 메뉴를 확인할 수 있습니다. 🍔🍣
- **저장 및 리셋**: 추천된 메뉴는 로컬 스토리지에 저장되며, "저장된 데이터 리셋" 버튼을 통해 저장된 데이터를 초기화할 수 있습니다. 🔄
- **삭제 기능**: 각 추천 항목 옆에 "삭제" 버튼을 눌러 해당 항목을 삭제할 수 있습니다. 🗑️

## 사용 방법 🛠️

1. **모델 선택**: 드롭다운 메뉴에서 원하는 모델("Gemini" 또는 "DeepSeek")을 선택합니다. 🎯
2. **메시지 입력**: 텍스트 영역에 점심 메뉴 추천을 받고 싶은 내용을 입력합니다. 💬
3. **등록 버튼 클릭**: "등록" 버튼을 클릭하면 선택한 모델에 맞는 점심 메뉴 추천이 표시됩니다. ✅
4. **저장된 데이터 리셋**: "저장된 데이터 리셋" 버튼을 클릭하면 로컬 스토리지에 저장된 모든 데이터가 삭제됩니다. 🔥
5. **삭제**: 각 추천 항목 옆에 있는 "삭제" 버튼을 클릭하여 해당 추천 항목을 삭제할 수 있습니다. ❌

## 기술 스택 🛠️

- ![HTML5](https://img.shields.io/badge/HTML5-FF6347?style=flat-square&logo=html5&logoColor=white) **HTML**: 웹 페이지의 기본 구조를 정의합니다. 🌐
- ![CSS3](https://img.shields.io/badge/CSS3-0077B5?style=flat-square&logo=css3&logoColor=white) **CSS**: 스타일을 지정하여 페이지를 꾸밉니다. 🎨
- ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) **JavaScript**: 로직을 처리하고, 사용자 인터랙션에 반응합니다. ⚡
- ![Fetch API](https://img.shields.io/badge/Fetch_API-FF4081?style=flat-square&logo=fetch&logoColor=white) **Fetch API**: 외부 서버와 데이터를 주고받기 위한 비동기 HTTP 요청을 처리합니다. 🌍
- ![LocalStorage](https://img.shields.io/badge/LocalStorage-4DBA87?style=flat-square&logo=html5&logoColor=white) **LocalStorage**: 추천 데이터를 로컬 스토리지에 저장하여 페이지가 새로고침되어도 데이터를 유지합니다. 💾

## API 엔드포인트 🌍

- **Gemini 모델**:
  - URL: `https://spotted-famous-seaplane.glitch.me/1`
  - 요청 방식: `POST`
  - 요청 데이터 형식: JSON
  - 응답: 점심 메뉴 추천 텍스트 🍜

- **DeepSeek 모델**:
  - URL: `https://spotted-famous-seaplane.glitch.me/2`
  - 요청 방식: `POST`
  - 요청 데이터 형식: JSON
  - 응답: 점심 메뉴 추천 텍스트 🍕 

## 개발 환경 설정 🖥️

1. GitHub에서 이 레포지토리를 클론합니다. 👾
2. `index.html` 파일을 브라우저에서 열어 웹 애플리케이션을 실행합니다. 🚀

---

맛있는 점심 메뉴를 고를 때마다 이 앱이 당신을 도와줍니다! 😋🍴
