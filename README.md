# 4주차 웹 프로그래밍

웹 응용 프로그래밍 네 번째 실습

1.과제 주제 : 웹 페이지 레이아웃 잡아보기

2.주요 코드
    1)맨 위의 메뉴바를 만들기 위한 플렉스 박스 생성
        -8개의 메뉴를 flex-item으로 선언하여 메뉴바 생성
        -border로 테두리를 만들어서 메뉴바 틀을 만듬

    2)메인 페이지의 이미지 박스 생성
        -메뉴에 해당하는 8개의 구역을 컨테이너 클래스로 구역을 나눔
        -뒤에 이미지를 넣을 공간 창출
        -오른편에 word-box클래스로 공간을 float으로 오른편에 생성

    3)밑에 주 내용들을 넣을 3개의 메인글들을 생성
        -main-box클래스를 생성해서 Main글들이 들어갈 틀 생성
        -asid, section을 선언해서 2개의 글을 가로로 나누어서 생성
        -마지막 Main글을 밑에 일자로 선언하여 마무리함

3.비고 및 고찰
    -이번 과제를 통해 웹 페이지의 구성을 할 박스들을 레이아웃하는 법을 연습할 수 있었다.

    -주로 어려웠던 점은 하나의 박스안에서 다시 여러개의 박스들을 레이아웃 하는 것이 어려웠고 가로 배열, 세로 배열을 자유롭게 구사하는 것이 어려웠다.
    
    -이미지를 넣고 싶었지만 이미지를 넣으면 그 위에 겹쳐서 레이아웃되어 따로 레이아웃하고 싶었지만 실패하여 그냥 이미지 자리를 알리기 위해 image position으로 선언했다.
    
    -가로 배열을 하는 것이 어려웠고 flex박스 밑에 바로 생성하는 것이 안돼 계산하여 margin값을 주어 레이아웃했다.
