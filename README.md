# PLUG·IN — 브라우저를 입히는 법

중간고사 대체 과제 · 학번 2601981 조서형

패션 코디를 주제로, 브라우저 확장 프로그램을 '액세서리'에 비유한 패션 잡지 스타일 브로슈어(16쪽)입니다.
**수업 자료(『HTML CSS 총정리』, 『입력 양식 태그와 구조화 태그』)에 나온 HTML5 태그와 CSS3 선택자·속성·단위만 사용**해 조판했습니다.

## 소주제
1. 플러그인이란 무엇인가
2. 나만의 필수 확장 프로그램 큐레이션
3. 확장 프로그램 설치 전 확인할 위험 신호

## 파일
| 파일 | 설명 |
|---|---|
| `index.html` | 브로슈어 전체 소스. 한 쪽 = `<section class="page">` 하나 (210×270mm) |

## 실행 방법
브라우저에서 `index.html`을 열면 16쪽이 세로로 이어져 보입니다.

## 사용한 수업 내용
- **HTML**: `h1`~`h5`, `p`, `br`, `hr`, `a`(href·id 링크), `b`, `ul`/`ol`/`li`, `table`/`thead`/`tbody`/`tr`/`th`/`td`(rowspan),
  `form`/`fieldset`/`legend`/`input type="checkbox"`/`label for`, `div`/`span`, `header`/`nav`/`section`/`article`/`aside`/`footer`
- **선택자**: 전체·태그·아이디·클래스(여러 개)·태그+클래스, 후손·자손, 동위(`+`), 구조(`:first-child`, `:last-child`, `:nth-child(2n)`)
- **속성**: 박스(width·height·margin·padding·border·border-radius), 가시(display), 배경(background-color·background-image·background-size),
  글자(font-*·text-align·line-height·text-decoration), 위치(position relative/absolute·left·top·z-index·overflow), 유동(float),
  목록(list-style), 그림자(box-shadow), 그레이디언트(linear-gradient)
- **단위**: mm, px, %, em, HEX 색상, 키워드
- 줄 바꿈·들여쓰기는 `<br>`과 특수 문자 `&nbsp;`로 표현
