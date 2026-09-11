# 💻 TriCode

> **Three Developers, One Code.**
> 함께 설계하고, 개발하고, 성장하는 소프트웨어 개발 팀 **TriCode**입니다.

<br>

## 👥 Team Members

|      이름     |                        GitHub ID                       |   역할 희망  |
| :---------: | :----------------------------------------------------: | :------: |
| 👩🏻‍💻 김서현 | [@kimseohyeon1533](https://github.com/kimseohyeon1533) | Frontend |
| 👨🏻‍💻 이준현 |                       @GitHub-ID                       |   역할 입력  |
| 👨🏻‍💻 최민혁 |                       @GitHub-ID                       |   역할 입력  |

<br>

## 🎯 Team Goal

단순한 기능 구현에 그치지 않고,
**요구사항 분석 → 설계 → 구현 → 테스트**의 과정을 체계적으로 진행하며
유지보수성과 확장성을 고려한 완성도 높은 소프트웨어 개발을 목표로 합니다.

<br>

## 🎯 Git Convention

| 이모지                   | 타입          | 설명                                     |
| --------------------- | ----------- | -------------------------------------- |
| 🎉 `Start`            | 프로젝트 시작     | 새로운 프로젝트 시작 (`:tada:`)                 |
| ✨ `Feat`              | 새로운 기능 추가   | 새로운 기능 구현 (`:sparkles:`)               |
| 🐛 `Fix`              | 버그 수정       | 오류 및 버그 해결 (`:bug:`)                   |
| 🎨 `Design`           | UI / CSS 수정 | UI 및 스타일 변경 (`:art:`)                  |
| ♻️ `Refactor`         | 리팩토링        | 코드 구조 및 품질 개선 (`:recycle:`)            |
| 🔧 `Settings`         | 설정 변경       | 환경설정 및 설정 파일 수정 (`:wrench:`)           |
| 🗃️ `Comment`         | 주석          | 필요한 주석 추가 및 변경 (`:card_file_box:`)     |
| ➕ `Dependency/Plugin` | 의존성 추가      | 라이브러리 및 플러그인 추가 (`:heavy_plus_sign:`)  |
| 📝 `Docs`             | 문서          | README 및 문서 수정 (`:memo:`)              |
| 🔀 `Merge`            | 병합          | 브랜치 병합 (`:twisted_rightwards_arrows:`) |
| 🚀 `Deploy`           | 배포          | 배포 관련 작업 (`:rocket:`)                  |
| 🚚 `Rename`           | 이름 변경       | 파일 및 폴더명 수정 또는 이동 (`:truck:`)          |
| 🔥 `Remove`           | 삭제          | 파일 및 코드 삭제 (`:fire:`)                  |
| ⏪ `Revert`            | 되돌리기        | 이전 버전으로 롤백 (`:rewind:`)                |

<br>

## 📝 Commit Message Convention

### 형식

```text
이모지 Type: 작업 내용 요약
```

### 예시

```text
✨ Feat: 로그인 기능 구현
🐛 Fix: 로그인 오류 해결
🎨 Design: 메인 페이지 UI 수정
♻️ Refactor: 회원가입 로직 구조 개선
📝 Docs: 팀원 정보 및 README 수정
```

<br>

## 🌿 Branch Convention

### Branch

* `main`

  * 최종 배포 및 안정화 브랜치
  * 항상 정상적으로 동작하는 상태 유지

* `develop`

  * 기능 개발이 통합되는 개발 브랜치
  * 각 작업 브랜치는 `develop`을 기준으로 생성

* `feature/#이슈번호/{description}`

  * 새로운 기능을 개발할 때 사용하는 브랜치

* `fix/#이슈번호/{description}`

  * 오류 및 버그를 수정할 때 사용하는 브랜치

* `design/#이슈번호/{description}`

  * UI 및 스타일 작업을 진행할 때 사용하는 브랜치

* `refactor/#이슈번호/{description}`

  * 코드 구조 개선 및 리팩토링 시 사용하는 브랜치

### 예시

```text
feature/#12/add-login-page
feature/#15/add-main-page
fix/#21/login-error
design/#25/main-ui
refactor/#31/user-api
```

<br>

## 🔀 Git Flow

### 1. Issue 생성

작업을 시작하기 전에 GitHub Issue를 생성하고 이슈 번호를 확인합니다.

```text
#12 로그인 기능 구현
```

### 2. 최신 `develop` 브랜치로 이동

```bash
git checkout develop
git pull origin develop
```

### 3. 이슈 번호를 포함한 작업 브랜치 생성

```bash
git checkout -b feature/#12/add-login-page
```

### 4. 작업 후 커밋

```bash
git add .
git commit -m "✨ Feat: 로그인 기능 구현"
```

### 5. 원격 저장소에 Push

```bash
git push origin feature/#12/add-login-page
```

### 6. Pull Request 생성

GitHub에서 Pull Request를 생성합니다.

```text
base    : develop
compare : feature/#12/add-login-page
```

PR 본문에는 관련 Issue를 연결합니다.

```text
Closes #12
```

팀원들의 코드 리뷰 후 `develop` 브랜치로 병합합니다.

### 7. 배포 시 `main`으로 병합

기능 개발 및 테스트가 완료되면

```text
develop → main
```

Pull Request를 생성하여 최종 검토 후 병합합니다.

<br>

## 🤝 Team Rules

* 작업 시작 전 GitHub Issue를 생성합니다.
* Branch 이름에 해당 Issue 번호를 포함합니다.
* 작업 시작 전 최신 `develop` 브랜치를 Pull합니다.
* 하나의 기능은 하나의 Branch에서 작업합니다.
* 다른 팀원의 Branch에 직접 Push하지 않습니다.
* `develop`과 `main` 브랜치에는 직접 Push하지 않습니다.
* 작업 완료 후 Pull Request를 생성합니다.
* Pull Request에 관련 Issue를 연결합니다.
* 팀원의 코드 리뷰 후 Merge를 진행합니다.
* Conflict가 발생하면 해당 작업자가 우선적으로 해결합니다.

<br>

---

<div align="center">

### 🧩 TriCode

**Three Developers, One Code.**

</div>
