# TRAVEL DART v2

## GitHub Pages에 올리는 파일

- `index.html`
- `dart.svg`

두 파일을 같은 폴더(보통 repository 루트)에 올립니다.

## 지도 데이터

`index.html`은 `southkorea/southkorea-maps`의 KOSTAT 2018 시군구 TopoJSON을 CDN/Raw URL에서 읽습니다.

지도는 모든 시군구 경계를 표시하고, 추첨 후보에서는 일반구를 제외합니다.
울릉군은 후보에서 제외하고 `울릉도·독도`를 하나의 별도 후보로 넣었습니다.

## 중요

지도 데이터는 2018 행정구역 경계이므로 최신 행정구역과 일부 차이가 있을 수 있습니다.
나중에 원하면 최신 경계 파일을 repository에 직접 넣어 외부 데이터 의존성을 없앨 수 있습니다.
