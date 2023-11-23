# README.md

## 실행순서

### `npm install`

'npm install' 명령을 통해 package.json을 참조하여 필요한 라이브러리를 node_modules디렉토리에 설치합니다.

### `npm start`

`npm start` 명령을 통해 프로젝트를 'http://localhost:3000'의 주소로 실행합니다.

## 프로젝트 구성

### 메인페이지

메인페이지는 'http://localhost:3000/'으로 라우팅되어 있습니다.
메인페이지에서는 오늘 진행중인 축제정보와 인기있는 축제정보를 확인할 수 있습니다.
또한 검색기능을 통해 축제를 검색하거나 원하는 축제정보를 바로 확인할 수 있습니다.

### 지역축제페이지

지역축제 페이지는 'http://localhost:3000/CountryDetail'으로 라우팅되어 있습니다.
지역축제 페이지에서는 지역별로 분류된 다양한 축제정보를 확인할 수 있습니다.
또한 지역별로 진행되는 축제 중에서도 인기있는 축제들과 진행중인 축제를 확인할 수 있습니다.
주어진 캘린더를 통해 원하는 날짜에 진행중인 지역축제를 확인할 수 있습니다.

### 축제 상세페이지

축제 상세페이지는 'http://localhost:3000/festival_detail/축제ID'로 라우팅되어 있습니다.
메인페이지/지역축제페이지/검색페이지/테마페이지 등에서 하나의 축제를 클릭하면 출력되는 페이지입니다.
해당하는 축제에 대한 세부적인 정보외에도 이미지정보와 카카오맵을 통한 지리정보를 확인할 수 있습니다.

### 검색페이지

축제 상세페이지는 'http://localhost:3000/SearchList'로 라우팅되어 있습니다.
검색페이지에서는 검색어를 통해 해당하는 축제정보를 확인할 수 있습니다.
검색결과로 나온 축제들은 지역별로 필터링이 가능합니다.

### 테마페이지
