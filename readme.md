# Python TIL

### 주의사항

맥에서는 내장된 python 2.7 version을 가지고 있지만, 해당 버전은 2020년 01월 이후로 지원이 중단됬다.

그리고 해당 파이썬은 제 3자에서도 많이 쓰고 있어서 해당 alias / path는 건들지 않는 것이 좋다.

그러므로, 새로운 python을 설치 후, 해당 python을 기준으로 작업한다.

---

### _Mac 에서 python3 설치_

```
  $ brew install pyton
```

해당 python3의 정보

```
  $ python3 -v
  Python 3.7.4
  $ which python3
  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3
```

### _python3 별칭 붙이기_

zsh를 쓰지 않는다면, bash_profile 에 삽입

python의 심링크는 /usr/local/bin/ 에 모여있다.

```
  $ echo "alias python=/usr/local/bin/python3" >> ~/.zshrc
  $ echo "alias pip=/usr/local/bin/pip3" >> ~/.zshrc
```

[_공식 페이지 튜토리얼 참조_](https://docs.python.org/ko/3.8/)

done
