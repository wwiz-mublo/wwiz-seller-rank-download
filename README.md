# Wwiz Seller Rank

네이버 쇼핑 상품 순위·가격비교 판매처 순위를 내 PC에서 추적하는 Windows 프로그램입니다.

## 내려받기

**[WwizSellerRank-Setup.exe 내려받기](https://github.com/wwiz-mublo/wwiz-seller-rank-download/releases/latest/download/WwizSellerRank-Setup.exe)**

- Windows 10 / 11 (64비트)
- Python 등 별도 프로그램 설치가 필요 없습니다. 내려받은 설치 파일을 실행하면 됩니다.
- 관리자 권한 없이 사용자 폴더(`%LOCALAPPDATA%\Programs\Wwiz Seller Rank`)에 설치됩니다.
- 디스크 여유 공간 2GB 이상이 필요합니다.

## 설치

1. 위 링크로 `WwizSellerRank-Setup.exe`를 내려받습니다.
2. 실행합니다. Windows SmartScreen이 "PC 보호" 창을 띄우면 **추가 정보 → 실행**을 누릅니다.
3. 설치가 끝나면 바탕화면 또는 시작 메뉴의 **Wwiz Seller Rank**를 실행합니다.

## 업데이트

프로그램을 켜면 새 버전을 확인하고, 설정의 **자동 업데이트**가 켜져 있으면 스스로 업데이트한 뒤 다시 시작합니다.
업데이트 파일은 서명과 SHA-256 해시를 확인한 뒤에만 설치됩니다. 직접 받으려면 위 설치 파일을 다시 실행해도 됩니다.

## 파일 확인

각 릴리스에는 `.sha256` 파일이 함께 있습니다. PowerShell에서 아래 명령의 결과와 비교할 수 있습니다.

```powershell
Get-FileHash .\WwizSellerRank-Setup.exe -Algorithm SHA256
```

## 제거

Windows 설정 → 앱 → **Wwiz Seller Rank** → 제거. 수집한 데이터(`%LOCALAPPDATA%\WwizSellerRank`)는 남겨 두므로, 완전히 지우려면 이 폴더를 직접 삭제하세요.

---

이 저장소는 배포 파일만 올리는 곳입니다. 소스 코드는 포함하지 않습니다.
