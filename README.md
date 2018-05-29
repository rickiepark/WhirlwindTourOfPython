# 회오리바람을 탄 파이썬

*제이크 반더플라스(Jake VanderPlas), 2016년 여름*

*박해선(https://tensorflow.blog), 2018년 봄*

*이 노트북은 제이크 반더플라스(Jake VanderPlas)의 [A Whirlwind Tour of Python](http://www.oreilly.com/programming/free/a-whirlwind-tour-of-python.csp)(OReilly Media, 2016)를 기반으로 만들어졌습니다. 전체 노트북의 목록은 https://github.com/rickiepark/WhirlwindTourOfPython 에서 볼 수 있습니다.*

*회오리바람을 탄 파이썬*은 다른 프로그래밍 언어를 이미 알고 있는 연구자와 개발자들에게 파이썬의 핵심 요소를 빠르게 전달하기 위한 안내서입니다. 파이썬을 데이터 과학이나 과학 프로그래밍에 사용하는데 촛점을 맞추었습니다.

이 노트북은 **파이썬 3.5**에서 테스트되었지만 어떤 파이썬 3.X 버전에서도 작동됩니다. 파이썬 2.X의 문법과 다른 점은 가능한 표기하도록 노력했습니다.

## 목차

*(노트: 깃허브의 노트북 렌더링이 느리거나 문제가 있을 때는 [nbviewer]((http://nbviewer.jupyter.org/github/rickiepark/WhirlwindTourOfPython/blob/master/Index.ipynb))를 사용하세요)*

[목차](https://github.com/rickiepark/WhirlwindTourOfPython/blob/master/목차.ipynb)

1. [소개](https://github.com/rickiepark/WhirlwindTourOfPython/blob/master/01-소개.ipynb)
2. [파이썬 코드를 실행하는 방법](https://github.com/rickiepark/WhirlwindTourOfPython/blob/master/02-파이썬 코드를 실행하는 방법.ipynb)
3. [파이썬 문법 빠르게 훑어 보기](https://github.com/rickiepark/WhirlwindTourOfPython/blob/master/03-파이썬 문법 빠르게 훑어 보기.ipynb)
4. [변수와 객체](https://github.com/rickiepark/WhirlwindTourOfPython/blob/master/04-변수와 객체.ipynb)
5. [연산자](https://github.com/rickiepark/WhirlwindTourOfPython/blob/master/05-연산자.ipynb)
6. [간단한 기본 데이터 타입](https://github.com/rickiepark/WhirlwindTourOfPython/blob/master/06-간단한 기본 데이터 타입.ipynb)
7. [기본 데이터 구조](https://github.com/rickiepark/WhirlwindTourOfPython/blob/master/07-기본 데이터 구조.ipynb)
8. [제어문](https://github.com/rickiepark/WhirlwindTourOfPython/blob/master/08-제어문.ipynb)
9. [함수](https://github.com/rickiepark/WhirlwindTourOfPython/blob/master/09-함수.ipynb)
10. [에러와 예외처리](https://github.com/rickiepark/WhirlwindTourOfPython/blob/master/10-에러와 예외처리.ipynb)
11. [반복자](https://github.com/rickiepark/WhirlwindTourOfPython/blob/master/11-반복자.ipynb)
12. [리스트 내포](https://github.com/rickiepark/WhirlwindTourOfPython/blob/master/12-리스트 내포.ipynb)
13. [제너레이터](https://github.com/rickiepark/WhirlwindTourOfPython/blob/master/13-제너레이터.ipynb)
14. [모듈과 패키지](https://github.com/rickiepark/WhirlwindTourOfPython/blob/master/14-모듈과 패키지.ipynb)
15. [문자열과 정규 표현식](https://github.com/rickiepark/WhirlwindTourOfPython/blob/master/15-문자열과 정규 표현식.ipynb)
16. [데이터 과학 도구 소개](https://github.com/rickiepark/WhirlwindTourOfPython/blob/master/16-데이터 과학 도구 소개.ipynb)
17. [Resources for Further Learning](https://github.com/rickiepark/WhirlwindTourOfPython/blob/master/16-Further-Resources.ipynb)
18. [Appendix: Code To Reproduce Figures](https://github.com/rickiepark/WhirlwindTourOfPython/blob/master/17-Figures.ipynb)

## 라이센스

이 노트북은 "No Rights Reserved" [CC0](https://github.com/jakevdp/WhirlwindTourOfPython/blob/master/LICENSE) 라이센스를 따릅니다. 따라서 어떤 목적으로도 재사용, 수정이 가능합니다.

CC0 라이센스에 대해서는 [여기](https://creativecommons.org/share-your-work/public-domain/cc0/)를 참고하세요.

이 노트북을 사용하려면 적절한 인용을 부탁합니다(하지만 필수는 아닙니다).

> *A Whirlwind Tour of Python* by Jake VanderPlas (O’Reilly). Copyright 2016 O’Reilly Media, Inc., 978-1-491-96465-1