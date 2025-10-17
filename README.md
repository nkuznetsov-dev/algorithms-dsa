# Algorithms & DSA — Go / JavaScript

**DSA (Data Structures & Algorithms)** — фундаментальные приёмы решения задач и структуры данных.
Здесь я собираю краткие решения на **Go** и **JavaScript** с пояснениями и оценкой сложности.

— Цель: тренировать мышление, чистый код и объяснимость решений.

## Стек
Go · JavaScript · простые бенчмарки/замеры (по мере надобности)

## Структура
- algorithms-dsa/
  - go/
    - arrays/
      - two-sum/
        - solution.go
        - solution_test.go
        - README.md
      - sliding-window-max/
        - solution.go
        - solution_test.go
        - README.md
    - hashmaps/
      - anagram-check/
        - solution.go
        - solution_test.go
        - README.md
    - linked-lists/
      - reverse-list/
        - solution.go
        - solution_test.go
        - README.md
    - graphs/
      - bfs/
        - solution.go
        - solution_test.go
        - README.md
  - js/
    - arrays/
      - two-sum/
        - index.js
        - index.test.js
        - README.md
    - hashmaps/
      - anagram-check/
        - index.js
        - index.test.js
        - README.md
    - linked-lists/
      - reverse-list/
        - index.js
        - index.test.js
        - README.md
    - graphs/
      - bfs/
        - index.js
        - index.test.js
        - README.md
  - templates/
    - README-problem.md          # шаблон описания задачи
    - go-solution.go             # заглушка с комментариями
    - go-solution_test.go        # заглушка тестов
    - js-solution.js             # заглушка с комментариями
    - js-solution.test.js        # заглушка тестов
  - .github/
    - workflows/
      - ci.yml                   # (позже) запуск тестов go/js
  - README.md


**Конвенции**
- Каждая папка темы (`arrays`, `graphs`…) содержит мини-задачи и `README.md` с краткими идеями и сложностями.
- Имена файлов говорят о приёме: `two-sum.go`, `bfs.js` и т. п.
- В описаниях решений фиксирую **Big-O** по времени/памяти.

## Как запускать (локально)
Go:
```bash
# пример запуска/тестов по мере добавления задач
go run ./go/arrays/two-sum.go
go test ./...   # когда появятся тесты
node js/arrays/two-sum.js
```
