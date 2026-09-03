# MIT 6.006 Feynman 교재

MIT OpenCourseWare의 **6.006 Introduction to Algorithms**를 따라가며 핵심 개념을 한국어로 다시 설명하고 직접 설명해 보는 개인 학습 교재입니다.

## 원칙

- MIT OCW의 강의·문제·해설은 복제하지 않고 공식 원문으로 연결합니다.
- HTML과 CSS만 사용하며 외부 프레임워크나 웹 폰트에 의존하지 않습니다.
- 본문은 고정 폭 대신 `max-width`로 제한하고 모든 요소에 `box-sizing: border-box`를 적용합니다.
- 긴 링크·코드는 줄바꿈하거나 가로 스크롤하며, 표는 `.table-wrap`으로 감쌉니다.
- 이미지와 영상은 컨테이너보다 커지지 않게 하고 모바일 글꼴과 터치 스크롤을 지원합니다.
- `viewport-fit=cover`와 safe-area 여백으로 노치가 있는 기기를 지원합니다.
- 다크 모드, 키보드 포커스, 인쇄용 레이아웃을 기본으로 제공합니다.

## Chapter 작성 규칙

1. 모든 장은 공통 `assets/css/book.css`와 `viewport-fit=cover` 메타 태그를 사용합니다.
2. 상단 목차는 JavaScript 없는 `<details class="toc">` 패턴을 사용하고 현재 링크에 `aria-current="page"`를 둡니다.
3. 본문 순서는 문제 → WHY → 개념/예제 → 불변식 또는 mental model → trade-off → 주의점 → 연습 → Feynman Test → 빈 종이 테스트입니다.
4. 끝에는 `.resources` 섹션을 두고 Lecture, Notes, Practice, Quiz 공식 링크를 표시합니다.
5. 마지막 `.chapter-nav`에는 이전/다음 장 또는 목차 링크를 둡니다.
6. 표는 `<div class="table-wrap">`으로 감싸고, 이미지에는 의미 있는 `alt`를 작성합니다.

## 구성

- `index.html`: 목차와 학습 경로
- `chapters/`: 장별 교재
- `assets/css/book.css`: 공통 반응형·인쇄 스타일
- `references/`: MIT OCW 공식 자료 링크

## 진도

- Part I · 계산을 보는 눈: Chapter 1–2 완료
- Part II · 자료를 담는 방식: Chapter 3–6 완료
- Part III · 순서를 만들어 문제를 푼다: Chapter 7–11 및 Quiz 1 Checkpoint 완료
- 전체: 11개 Chapter + 1개 Checkpoint 완료

| Chapter | 주제 | 상태 |
| --- | --- | --- |
| 1 | 알고리즘과 정확성 | 완료 |
| 2 | Big-O와 점근 분석 | 완료 |
| 3 | Sequence vs Set, interface-first thinking | 완료 |
| 4 | 정적 배열 | 완료 |
| 5 | 연결 리스트 | 완료 |
| 6 | 동적 배열과 분할상환 분석 | 완료 |
| 7 | 정렬을 중간 표현으로 사용하기 | 완료 |
| 8 | Selection Sort와 Insertion Sort | 완료 |
| 9 | Merge Sort와 분할정복 | 완료 |
| 10 | 비교 정렬 하한 | 완료 |
| 11 | Counting Sort와 Radix Sort | 완료 |
| Checkpoint | Chapter 3–11 Quiz 1 통합 복습 | 완료 |

## 참고

- [MIT OCW 6.006 Introduction to Algorithms (Fall 2011)](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/)
- [MIT OCW 6.006 Introduction to Algorithms (Spring 2020)](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/)

이 저장소는 MIT의 공식 번역물이나 배포물이 아닙니다.
