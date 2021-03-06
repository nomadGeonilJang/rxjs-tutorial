# RxJS 란?
# start

## 리액티브 프로그래밍 이란?

1. 리액티브 프로그래밍이란 데이터 스트림과 변화의 전이를 통한 `비동기 프로그래밍` 패러다임이다.
  - 선언형 프로그래밍 vs 리액티브 프로그래밍
  - A 택배 도착 알림함 -> 백배라는 데이터 흐름을 나타냄 -> 데이터 스트림 택배 도착 알림함에 알람이 울리면 A 집에서 B 집으로 택배를 옮겨 -> B 택배 도착 알림하이 울린다 -> 변화의 전의!
#### 선언형 프로그래밍이란?
1. 프로그램이 `어떤 방법으로`해야 하는지를 나타내기보다 `무엇`과 같은지를 설명하는 경우에 "선언형" 이라고 한다.
  - A라는 사람의 집에 택배가 오면 B하는 사람의 집에다 옮겨.
#### 명령형 프로그래밍

1. 컴퓨터가 수행할 명령의 모음으로써 프로그래밍을 한다.
2. 컴퓨터가 어떻게 작업을 수행하는 지에 대해 설명한다.
  - A라는 사람의 집에 있는 택배를 B라는 사람의 집으로 옮겨 다 했으면 계속 반복해

## Observable 이란?
1. Data Stream이라는 추상적인 개념을 구현한 구현제이다.
- 즉, Observable을 구동하고 Observable에서 다양한 값들이 발생하면 이를 받아서 어떤 행동을 취한다.
 
- Data Stream이란?
  - 시간에 따른 이벤트 흐름?
 ![data](./static/data.png)
> 시간이 흐르는 동안 택배하 하나씩 도착 할 때만다 어느 행동을 한다.


## 설치

- 개발 환경 셋팅하기.

```bash
npm i -g rxjs
```


- [1] [from of](./01_from_of/index.d.js)
- [2] [interval timer](./02_interval_timer/index.d.js)
- [3] [concat_merge](./03_concat_merge/index.d.js)
- [4] [filter_map_reduce_tap](./04_filter_map_reduce_tap/index.d.js)