# 오픈소스 소프트웨어 파이썬 시험준비

## 파이썬

## 파이썬 자료구조2
### 자료구조
- 자료구조란 자료들을 저장하는 데이터 구조를 말한다
- 파이썬의 기초적인 자료구조는 시퀀스(sequence)이다. 
- 시퀀스는 요소(element)ㄹ 구성되어 있고 요소 간에는 순서가 있다. 시퀀스의 요소들은 번호(index)를 부여받는다.
- 파이썬은 6개의 내장 시퀀스(str, bytes, bytearray, list, tuple, range)를 가지고 있다. 
- 시퀀스에 속하는 자료구조들은 동일한 연산을 지원한다.
- `indexing``slicing``adding``multiplying`등

### 튜플(tuple)
-리스트와 다르게 튜플은 변경 불가능하다.
-리스트와 다르게 튜플은 딕셔너리의 키로 사용할 수 있다.
```
  tuple = ()
  tuple_1 = ("apple",) #쉼표가 필요하다
  tuple_2 = "apple","banana"
```
- 튜플 패킹과 언패킹
```
  x = ("apple","banana","grape")
  (s1,s2,s3) = x
```
- enumerate()
- 반복 가능한 객체(리스트나 튜플)를 받아서 각요소에 대해 (인덱스,값) 형태의 튜플을 반환한다.
### 세트(set)
- set는 우리가 수학에서 배웠던 집합이다.
- 고유한 값들을 저장하는 자료구조라고 할 수 있다.
- 세트의 요소는 특정 순서로 저장되지 않으며 위치별로 엑세스 할 수 없다.
```
  sets = {1,2,3}
  sets_1 = set() # 공백 세트를 생성한다.
  sets_2 = set([1,2,3,1,2,3]) # {1,2,3}
  sets_3 = set("abc") # {'a','b','c'}
```
- `|`,`union()` 합집합, `&``intersection()` 교집합, `-``difference()` 차집합
```
세트 연산 정리
 set() 공백 세트 생성
 set(seq) 시퀀스에서 요소를 꺼내서 세트를 만든다.
 set = {e1,e2,e3} 초기값이 있는 세트는 중괄호로 만든다
 len(set) 세트에 있는 요소의 수
 x in set 세트안에 요소 있는지 여부
 .add(e1) 세트안에 
 .remove(e1)
 .discard(e1)
 .clear()
 set.issubset(s1)
 s1 == s2
 s1 != s2
 s2.union(s1) s2|s1
 s2.intersection(s1) s1&s2
 s2.difference(s1) s2-s1
```
### 딕셔너리(dictionary)
- 값(value)와 키값(key)을 함께 저장하는 자료구조
- 






