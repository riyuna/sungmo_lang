# sungmo_lang
쇼미더 럭키짱, 럭키짱 등에서 나온 밈들로 이루어진 난해한 언어입니다.

## 변수의 선언

변수는 사용하는 순간 선언됩니다. 명시적으로 선언할 필요는 없습니다.

## 변수의 할당

다음 문법을 통해 변수를 할당할 수 있습니다.

```
(변수명)이... 말대꾸??
(변수명)가... 말대꾸??
```

`.`의 개수는 2개 이상, `?`의 개수는 1개 이상이어야 합니다.
이 경우 할당되는 값은 `(.의 개수 - 1) * (?의 개수)`입니다.

만일 음수를 할당하고 싶을 경우, `?` 뒤에 `!`을 추가하면 됩니다.
할당되는 값은 `-1 * (.의 개수 - 1) * (?의 개수)`입니다.

0을 할당하고 싶다면, `?` 사이에 `!`을 넣으면 됩니다.

예시는 다음과 같습니다.

```
꼬맹이가... 말대꾸?? (꼬맹이 = 4)
할아버지가.. 말대꾸??! (할아버지 = -2)
학생회장이... 말대꾸?!? (학생회장 = 0)
```

## 변수의 해제

다음 문법을 통해 변수를 해제할 수 있습니다.

```
(변수명)은 어차피 놔둬도 자연사야!
(변수명)는 어차피 놔둬도 자연사야!
```

모든 변수를 할당하고 싶으면 `어차피 놔둬도 자연사야!`를 사용하면 됩니다.

## 반복문

다음 문법을 통해 반복문을 사용할 수 있습니다.

```
받아랏! (정수) 컴보!
...
더 이상의 자세한 설명은 생략한다.
```

블록 안에 있는 코드를 `정수`번 반복합니다.

만일 변수의 값 만큼 반복하고 싶으면 `받아랏! (변수명)의 컴보!`를 사용하면 됩니다.
