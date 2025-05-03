# Use Case Descriptions

## 📌 Use Case: 회원 가입

- **Actor**: 회원
- **Trigger**: 회원이 가입 화면에서 정보를 입력하고 제출
- **Preconditions**: 사용자는 계정이 없어야 함
- **Main Flow**:
    1. 회원이 가입 페이지에 접속한다.
    2. ID, 비밀번호, 전화번호, 결제 수단, 선호 자전거 유형을 입력한다.
    3. 가입 버튼을 누른다.
    4. 시스템이 정보를 저장한다.
    5. 가입 성공 메시지를 출력한다.
- **Alternate Flow**:
    - ID 중복 시, 중복 알림을 띄우고 재입력을 유도한다.

![reqdescription.png](reqdescription.png)

## 회원 가입

| **회원 가입** |  |
| --- | --- |
| Actor Action | System Response |
| 1. None | 2. 회원 정보를 입력받기 위한 필드들을 표시한다 |
| 3. 필드에 회원 정보를 입력하고 제출 버튼을 누른다 | 4. 필수 입력 정보가 모두 입력되었고 이미 가입된 ID가 아닌 경우, 회원 가입 성공 알림을 표시한다 |
| Alternative Courses |  |
| None |  |
| Extensions |  |
| None |  |
| Exceptions |  |
| 4-1. 필수 입력 정보가 모두 입력되지 않은 경우, 필수 입력 정보 중 입력되지 않은 필드를 강조 표시한다 |  |
| 4-2. 이미 가입된 ID인 경우, 이미 가입된 ID임을 안내하는 문구를 ID 필드 옆에 표시한다 |  |

---

## 회원 탈퇴

| **회원 탈퇴** |  |
| --- | --- |
| Actor Action | System Response |
| 1. None | 2. 회원 탈퇴 버튼을 표시한다 |
| 3. 회원 탈퇴 버튼을 누른다 | 4. 탈퇴 완료 알림을 표시한다 |
| Alternative Courses |  |
| None |  |
| Extensions |  |
| None |  |
| Exceptions |  |
| None |  |

---

## 로그인

| **로그인** |  |
| --- | --- |
| Actor Action | System Response |
| 1. None | 2. ID와 비밀번호 필드를 표시한다 |
| 3. ID와 비밀번호를 입력한다 | 4. 입력된 ID와 비밀번호가 유효하고 회원의 ID인 경우 회원으로 로그인된 화면을 표시하고, 입력된 ID와 비밀번호가 유효하고 관리자의 ID인 경우 관리자로 로그인된 화면을 표시한다 |
| Alternative Courses |  |
| None |  |
| Extensions |  |
| None |  |
| Exceptions |  |
| 4-1. 입력된 ID나 비밀번호가 유효하지 않은 경우, ID 혹은 비밀번호가 유효하지 않다는 알림을 표시한다 |  |

---

## 로그아웃

| **로그아웃** |  |
| --- | --- |
| Actor Action | System Response |
| 1. None | 2. 로그아웃 버튼을 표시한다 |
| 3. 로그아웃 버튼을 누른다 | 4. (로그아웃 되었으므로)로그인 화면을 표시한다 |
| Alternative Courses |  |
| None |  |
| Extensions |  |
| None |  |
| Exceptions |  |
| None |  |

---

## 전체 대여소 리스트 조회 (관리자)

---

## 대여소 등록

---

## 관리자 대여소 상세정보 조회

---

## 회원 대여소 상세정보 조회

---

## 조건에 맞는 대여소 리스트 조회

---

## 자전거 리스트 조회

---

## 자전거 등록

---

## 대여중인 자전거 조회

---

## 자전거 상세내용 보기

---

## 자전거 예약대기 정보 조회