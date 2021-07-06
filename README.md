# vue-diary project

> 처음으로 Vue.js를 사용해 만들어 보는 프로젝트, 다이어리

<img src="/Users/uhjee/Desktop/git_remote/vue_diary/images/login.png" style="width:50%;" />

<img src="/Users/uhjee/Desktop/git_remote/vue_diary/images/list.png" style="width:50%;" />

<img src="/Users/uhjee/Desktop/git_remote/vue_diary/images/write.png" style="width:50%;" />

## About

- Vue를 배우고 익숙해지기 위해 진행한 다이어리 프로젝트
- Vuex의 Store에 일기를 저장하도록 하며, 기본적인 CRUD 구현
- 효율적인 컴포넌트 구조를 위해 고민하며 진행(중복 코드가 최대한 발생하지 않도록...)
- vue-router를 통해 SPA에서의 routing 개념 숙지

## Stack

- Vue(3.5.1)
- Element-UI
- Webpack
- Babel
- Vuex
- vue-router
- Postcss, Autoprefixer

## Features

- 로그인 화면(실제 로그인이 아닌 Vuex 의 상태관리 연습을 위한 로그인 화면, 사용자의 Id는 Store에 담아둔다)
- 다이어리 CRUD
- 다이어리 조회 시, 타임라인 또는 카드형으로 조회 가능
- 추가, 수정과 같이 거의 유사한 컴포넌트는 하나로 구현한 뒤, 상태(mode)로 전환되도록 처리

