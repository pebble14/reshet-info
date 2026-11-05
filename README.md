# Reshet

Reshet는 성경 원어 단어의 뜻과 관계를 탐구하는 도구입니다. Strong 번호, 원어 표기, 음역, 발음, 의미로 단어를 검색하고 관계 그래프를 따라 연결된 단어를 살펴볼 수 있습니다.

이 도구가 성경을 더 깊이 읽고 복음을 접하는 작은 계기가 되기를 바랍니다. 소스코드는 누구나 자유롭게 활용하고 발전시킬 수 있도록 MIT 라이선스로 공개하고 있습니다.

## 주요 기능

- 성경 원어 단어 검색과 상세 정보 확인
- 관계 그래프를 통한 단어 관계 탐색
- 단어 정보·메모와 관계 편집
- SQLite DB 전체 백업·복원

Windows와 Android에서 사용하는 앱입니다. 데이터는 로컬 SQLite에 저장하며, 뜻풀이·메모·관계는 계속 연구하고 검토합니다.

## 소개 영상

[성경 원어, 뜻에서 관계로 | Reshet Windows 공개 베타](https://youtu.be/dnk0g0TkheQ)

36초 영상으로 단어의 뜻과 관계 그래프를 탐색하는 모습을 살펴보세요.

## Windows 공개 베타 다운로드

[Reshet 1.0.0-beta.1 — Windows x64 배포 페이지](https://github.com/pebble14/reshet_app/releases/tag/v1.0.0-beta.1)

- [Windows 앱 ZIP 다운로드](https://github.com/pebble14/reshet_app/releases/download/v1.0.0-beta.1/Reshet-1.0.0-beta.1-windows-x64.zip): 일반 사용자는 이 파일 하나만 받으면 됩니다. 데이터 버전 `2026.11.04`의 DB가 포함되어 있습니다.
- ZIP을 완전히 풀고 `study.exe`를 실행하세요. DLL과 `data` 폴더를 함께 두세요. 실행 파일은 코드 서명되지 않은 베타입니다.
- 기존 사용자 DB는 자동으로 덮어쓰지 않습니다. 새 제공 데이터를 사용하려면 먼저 외부 백업을 저장한 뒤 앱의 `제공 데이터로 전체 교체`를 선택하세요. 기존 편집 내용과 병합되지 않습니다.
- [별도 DB ZIP](https://github.com/pebble14/reshet_app/releases/download/v1.0.0-beta.1/Reshet-data-2026.11.04.zip)은 데이터만 필요한 개발자·연구자용 선택 다운로드입니다.
- 배포 페이지에 파일 확인용 `SHA256SUMS.txt`가 있습니다. GitHub의 `Source code` 압축 파일은 실행 프로그램이 아닙니다.

## 코드 활용과 출처 안내

[Reshet 소스 저장소](https://github.com/pebble14/reshet_app)에서 공개된 소스코드, MIT 라이선스와 개발 안내를 확인할 수 있습니다.

MIT는 수정·재배포·상업적 이용을 허용하며 수정판의 소스코드 공개를 요구하지 않습니다. 코드 또는 그 상당 부분을 재배포할 때 원저작권 표시와 MIT 라이선스 전문을 유지해야 합니다. DB·어휘 연구 데이터와 외부 자료의 이용 조건은 코드 MIT와 별도로 구분합니다.

Reshet를 활용한 프로그램이나 문서에는 아래 문구로 출처를 안내해 주시면 좋겠습니다. 소개 링크와 아래 문구는 권장 사항이며 MIT에 추가되는 의무 조건은 아닙니다. 이 문구는 원저작권 표시와 라이선스 전문을 대신하지 않습니다.

```text
Reshet의 소스코드를 활용했습니다.
프로젝트 소개: https://github.com/pebble14/reshet-info/blob/main/README.md
소스코드: https://github.com/pebble14/reshet_app
코드 라이선스: MIT
```

## 개인정보처리방침

[Reshet 개인정보처리방침](https://pebble14.github.io/reshet-info/privacy_policy.html)을 확인해 주세요.
