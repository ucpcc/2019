---
layout: default
---

<div class="main-pic-wrapper">
  <img id="main-pic" src="">
  <div class="main-pic-overlay"></div>
  <div class="main-pic-overlay-text">
    전국 대학생 프로그래밍 대회 동아리 연합 <br />
    여름 대회 2019
  </div>
</div>

## Update

- *19.07.28 : 예선 [스코어보드](https://ucpc.acmicpc.net/contest/spotboard/449)가 공개되었습니다.*
- *19.07.27 : UCPC2019 온라인 예선이 종료되었습니다. 문제와 풀이를 공개했습니다. [예선 대회 안내 페이지]({% link 02-qualifier.md %})에서 확인할 수 있습니다.*
- *19.07.26 : 팀별 계정을 메일로 전송하였습니다. 예선 예비소집 및 온라인 대회는 https://ucpc.acmicpc.net/info 에서 진행됩니다.*
- *19.07.25 : **스태프** 모집 내용이 업로드되었습니다.*
- *19.07.25 : **예선 예비소집 일정과 본선 일정**이 공지되었습니다.*
- *19.07.07 : [참가 현황](https://docs.google.com/spreadsheets/d/1ps3LDcKXaZqVgQu4lhjAu9pmDPv9ZL4DH6iSIiIoam4/edit?usp=sharing)을 공유하였습니다. 이전 링크로는 수정하실 수 없습니다. 이후 수정 및 확인 관련 문의사항은 이메일로 연락해주세요.*
- *19.07.06 : 참가 신청이 마감되었습니다. 신청자 목록은 7.9(화)전까지 정리하여 공지할 예정입니다.*
- *19.07.05 : 참가 신청 마감 이후, 총괄적으로 팀 정보 수정 요청을 처리할 예정입니다.*
- *19.07.01 : 참가 신청 기간을 7월 5일(금)까지 연장하였습니다.*
- *19.06.25 : 참가 신청 현황을 공개했습니다.*
- *19.06.22 : 본선 날짜는 8월 3일(토)입니다.*

공지는 [전대프연 공식 페이스북 그룹](https://web.facebook.com/groups/250186671672125?_rdc=1&_rdr)에 업로드하고 있습니다.

## UCPC 2019

UCPC는 전국 대학생 프로그래밍 대회 동아리 연합(이하 전대프연)에서 진행하는 여름 대회입니다.
2011년 제1회 UCPC를 시작으로 올해 제8회 UCPC를 준비하고 있습니다.

ACM-ICPC 대전 리저널과 유사한 형식으로 온라인 예선, 본선이 나눠져 진행됩니다.

ACM-ICPC를 준비하는 학생, 프로그래밍 대회에 관심이 있는 학생, 그냥 참가하고 싶은 학생 모두에게
좋은 경험이 될 것이니 많이 기대해주세요!

## 대회 일정

 * 참가 접수 : **~ 2019년 7월 5일 23:59**
 * 온라인 예선 : **2019년 7월 27일(토) 14:00 ~ 17:00**
 * 본선 : **2019년 8월 3일(토) 10:00 ~ 19:30 : 고려대학교 하나스퀘어**

## 참가 신청

현재 참가팀 신청은 마감되었습니다.
참가와 관련된 자세한 안내는 [대회 안내]({% link 01-about.md %}) 페이지를 참고해주세요.
참가 신청이 제대로 되었는지 확인하고 싶다면 아래 참가 신청 현황 페이지를 확인해주세요.

- 참가 신청 마감
- [참가 현황(공유)](https://docs.google.com/spreadsheets/d/1ps3LDcKXaZqVgQu4lhjAu9pmDPv9ZL4DH6iSIiIoam4/edit?usp=sharing)

참가 관련 문의 사항이 있다면 ucpc.kr@gmail.com 또는 subinium@gmail.com으로 연락주세요.

---
# Sponsor

## 전국대학생프로그래밍대회동아리연합
## 삼성전자 & 삼성 소프트웨어멤버십
## Algospot
## Startlink (BOJ)
## 리얼리티리플렉션
## KENNYSOFT
## 루트원소프트
## 고려대학교 소프트웨어중심사업단

<script type="text/javascript">
  function lpad(num, pad_str, len) {
    var str = num.toString();
    while (str.length < len) {
      str = pad_str + str;
    }
    return str;
  }
  window.onload = function () {
    var picture_num = Math.floor(Math.random() * 10);
    var picture_name = 'main-pic-' + lpad(picture_num, '0', 2) + '.jpg';
    var path = '{{ "/assets/" | relative_url }}' + picture_name;
    document.getElementById('main-pic').src = path;
  };
</script>
