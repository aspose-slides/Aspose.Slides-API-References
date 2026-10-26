---
title: MathBlock
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: MathParagraph에 포함되고 자체 라인에서 시작되는 수학 텍스트 인스턴스를 지정합니다.
type: docs
url: /ko/com.aspose.slides/mathblock/
---
**상속:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject  
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

MathParagraph 내에 포함되고 자체 라인에서 시작되는 수학 텍스트 인스턴스를 지정합니다. 방정식, 표현식, 방정식 또는 표현식 배열, 그리고 수식 등을 포함한 모든 수학 영역은 math block으로 표현됩니다.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathBlock()](#MathBlock--) | MathBlock 클래스의 새 인스턴스를 초기화합니다. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | 새로운 수학 블록을 만들고 지정된 요소를 넣습니다 |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | 새로운 수학 블록을 만들고 지정된 여러 요소를 넣습니다 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCount()](#getCount--) | 컬렉션에 실제로 포함된 하위 수학 요소의 수를 가져옵니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에서 IMathElement를 가져오거나 설정합니다. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | 지정된 인덱스에서 IMathElement를 가져오거나 설정합니다. |
| [isReadOnly()](#isReadOnly--) | 하위 요소 컬렉션을 수정할 수 있기 때문에 false를 반환합니다. |
| [getChildren()](#getChildren--) | 하위 요소를 가져옵니다 |
| [getParent_Immediate()](#getParent-Immediate--) | Parent_Immediate 개체를 반환합니다. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | 컬렉션 끝에 수학 요소를 추가합니다. |
| [clear()](#clear--) | 컬렉션의 모든 요소를 제거합니다. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | 컬렉션에 특정 값이 포함되어 있는지 확인합니다. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | 지정된 배열에 복사합니다. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 반복자를 반환합니다. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | 컬렉션에서 특정 수학 요소의 인덱스를 결정합니다. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | 지정된 인덱스에 MathElement를 삽입합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에서 요소를 제거합니다. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | 수학 요소를 이 수학 블록과 결합합니다 |
| [join(String mathText)](#join-java.lang.String-) | 수학 텍스트를 이 수학 블록과 결합합니다 |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | 다른 수학 블록을 이 블록과 결합합니다 |
| [delimit(char separatorCharacter)](#delimit-char-) | 괄호 없이 구분 문자로 하위 요소를 구분합니다 |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | 괄호 또는 기타 문자와 같은 지정된 문자로 이 블록의 하위 요소를 둘러싸고 프레이밍합니다 |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | 괄호 또는 기타 문자와 같은 지정된 문자로 이 블록의 하위 요소를 둘러싸고 구분 문자로 구분합니다 |
| [toMathArray()](#toMathArray--) | 하위 요소를 수직 배열에 배치합니다 |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | 이 [MathBlock](../../com.aspose.slides/mathblock)의 내용을 MathML로 저장합니다 |
### MathBlock() {#MathBlock--}
```
public MathBlock()
```

MathBlock 클래스의 새 인스턴스를 초기화합니다.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```


### MathBlock(IMathElement mathElement) {#MathBlock-com.aspose.slides.IMathElement-}
```
public MathBlock(IMathElement mathElement)
```

새로운 수학 블록을 만들고 지정된 요소를 넣습니다

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 블록에 넣을 수학 요소 |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

새로운 수학 블록을 만들고 지정된 여러 요소를 넣습니다

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | 블록에 넣을 수학 요소들 |

### getCount() {#getCount--}
```
public final int getCount()
```

컬렉션에 실제로 포함된 하위 수학 요소의 수를 가져옵니다. 읽기 전용 int.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**반환값:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

지정된 인덱스에서 IMathElement를 가져오거나 설정합니다.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 항목의 0부터 시작하는 인덱스 |

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement) - 수학 요소.

### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

지정된 인덱스에서 IMathElement를 가져오거나 설정합니다.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 항목의 0부터 시작하는 인덱스 |
| value | [IMathElement](../../com.aspose.slides/imathelement) | 수학 요소. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

하위 요소 컬렉션을 수정할 수 있기 때문에 false를 반환합니다.

**반환값:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

하위 요소를 가져옵니다

**반환값:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 개체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

컬렉션 끝에 수학 요소를 추가합니다.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 컬렉션 끝에 추가될 IMathElement. |

### clear() {#clear--}
```
public final void clear()
```

컬렉션의 모든 요소를 제거합니다.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public final boolean contains(IMathElement item)
```

컬렉션에 특정 값이 포함되어 있는지 확인합니다.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  boolean contains = mathBlock.Contains(plusElement);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 컬렉션에서 찾을 객체. |

**반환값:**
boolean - 컬렉션에 아이템이 있으면 true, 없으면 false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

지정된 배열에 복사합니다.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[mathBlock.Count];
>  mathBlock.copyTo(destinationArray, 0);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | 복사 대상 배열. |
| arrayIndex | int | 복사를 시작할 인덱스. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.Remove(plusElement);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 컬렉션에서 제거할 객체. |

**반환값:**
boolean - 컬렉션에서 아이템이 성공적으로 제거되면 true, 그렇지 않으면 false. 아이템이 원본 컬렉션에 없을 경우에도 false를 반환합니다.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - 컬렉션을 순회할 수 있는 IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

전체 컬렉션에 대한 java 반복자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.IEnumerator - 전체 컬렉션에 대한 java.util.Iterator.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

컬렉션에서 특정 수학 요소의 인덱스를 결정합니다.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = mathBlock.indexOf(plusElement);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 컬렉션에서 찾을 요소. |

**반환값:**
int - 컬렉션에 아이템이 있으면 인덱스, 없으면 -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

지정된 인덱스에 MathElement를 삽입합니다.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | MathElement를 삽입할 0부터 시작하는 인덱스. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 삽입할 MathElement. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

지정된 인덱스에서 컬렉션 요소를 제거합니다.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.removeAt(2);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 요소의 0부터 시작하는 인덱스. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

수학 요소를 이 수학 블록과 결합합니다

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 결합할 요소 |

**반환값:**
[IMathBlock](../../com.aspose.slides/imathblock) - 현재 IMathBlock 인스턴스
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

수학 텍스트를 이 수학 블록과 결합합니다

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathText | java.lang.String | 결합할 수학 텍스트 |

**반환값:**
[IMathBlock](../../com.aspose.slides/imathblock) - 이 인스턴스와 지정된 인자를 포함하는 새로운 IMathBlock
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

다른 수학 블록을 이 블록과 결합합니다

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | 결합할 블록 |

**반환값:**
[IMathBlock](../../com.aspose.slides/imathblock) - 결합 후 이 수학 블록
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

구분 문자(괄호 없이)로 하위 요소를 구분합니다

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| separatorCharacter | char | 구분 문자 |

**반환값:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 유형의 수학 요소
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

괄호 또는 기타 문자와 같은 지정된 문자로 이 블록의 하위 요소를 둘러싸고 프레이밍합니다

--------------------

> ```
> Example:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| beginningCharacter | char | 시작 문자(보통 왼쪽 괄호) |
| endingCharacter | char | 끝 문자(보통 오른쪽 괄호) |

**반환값:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 지정된 문자로 프레이밍된 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 유형의 수학 요소
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

괄호 또는 기타 문자와 같은 지정된 문자로 이 블록의 하위 요소를 둘러싸고 구분 문자로 구분합니다

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| beginningCharacter | char | 시작 문자(보통 왼쪽 괄호) |
| endingCharacter | char | 끝 문자(보통 오른쪽 괄호) |
| separatorCharacter | char | 구분 문자 |

**반환값:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 지정된 문자로 프레이밍되고 구분 문자가 포함된 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 유형의 수학 요소
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

하위 요소를 수직 배열에 배치합니다

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**반환값:**
[IMathArray](../../com.aspose.slides/imatharray) - [IMathArray](../../com.aspose.slides/imatharray) 유형의 새 인스턴스
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

이 [MathBlock](../../com.aspose.slides/mathblock)의 내용을 MathML로 저장합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 대상 스트림 |