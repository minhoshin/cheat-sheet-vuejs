# cheat-sheet-vuejs

## chrome 브라우저 설정
Chrome DevTools 에서 Vue.js devtools

## vscode 설정
1. EXTENSIONS 에서 Vetur, Material Icon Theme, Night Owl, Live Server, Rainbow Brackets, Auto Close Tag 설치
2. Code - Preferences - File Icon Theme 에서 Material Icon Theme 선택
3. Code - Preferences - Color Theme 에서 Night Owl 선택
- Vetur : Vue.js 플러그인
- Night Owl : 코드 하이라이팅 플러그인\
- Material Icon Theme : 폴더 아이콘 테마
- ESLint : 자바스크립트 문법 검사 플러그인
- TSLint : 타입스크립트 문법 검사 플러그인
- Auto Close tag : HTML 태그 자동 닫기 플러그인
- Live Server : 정적 파일을 로컬 서버에 올리고 자동 갱신해주는 플러그인

## 서버 실행
좌측 EXPLORER 파일 우측 버튼 또는 우측 소스 우측 버튼 Open with Live Server 를 통해 실행

## chrome 개발자 도구에서
command + option + i 후 vue 라는 패널 선택 그 중 Components 와 Events 많이 사용

## 손쉬운 html 생성
html 파일에서 !입력후 엔터 치면 기본 html 코드 생성

## Auto Close Tag EXTENSIONS 설치 효과
html 파일에서 div#app 하고 엔터 치면 ```<div id="app"></div>``` 생성

## vue cli 검색 및 설치 그리고 프로젝트 생성 및 실행
```
$ npm install -g @vue/cli
$ vue --version
$ vue create project-name
$ cd projetct-name
$ npm run serve
```

## vue Scaffold 생성
.vue 생성 후 vue 입력 후 탭 또는 엔터
아래 Scaffold 설명
```
<template>
  <!-- HTML -->
</template>

<script>
export default {
    // Javascript
}
</script>

<style>
    /* css */
</style>
```

## ESLint 초기 설정
VS Code 팔레트를 열고 create ESLINT Configuration 실행

## Vue 에서 ESLint 에러를 표시하지 않으려면
https://cli.vuejs.org/config/#lintonsave
프로젝트 폴더에 `vue.config.js` 파일 생성 후 아래 내용 입력
```
module.exports = {
  lintOnSave: false
}
```

## npm
vue router
vuex

