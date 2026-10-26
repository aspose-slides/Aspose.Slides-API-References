---
title: IMathElementCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 수학 요소 MathElement의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/imathelementcollection/
---
**모든 구현된 인터페이스:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

Represents a collection of mathematical elements (MathElement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [getCount()](#getCount--) | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | 수학 요소를 컬렉션의 끝에 추가합니다. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | 컬렉션에서 특정 수학 요소의 인덱스를 결정합니다. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | 지정된 인덱스에 수학 요소를 삽입합니다. |
| [clear()](#clear--) | 컬렉션의 모든 요소를 제거합니다. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | 컬렉션에 특정 값이 포함되어 있는지 확인합니다. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션의 지정된 인덱스에 있는 요소를 제거합니다. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | 지정된 배열에 복사합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```

지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [IMathElement](../../com.aspose.slides/imathelement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 가져올 항목의 0부터 시작하는 인덱스 |

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```

컬렉션에 실제로 포함된 요소 수를 가져옵니다. 읽기 전용 int.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**반환값:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```

수학 요소를 컬렉션의 끝에 추가합니다.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 컬렉션의 끝에 추가될 IMathElement |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```

컬렉션에서 특정 수학 요소의 인덱스를 결정합니다.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = collection.indexOf(plusElement);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 컬렉션에서 찾을 요소 |

**반환값:**
int - 컬렉션에서 항목을 찾으면 해당 인덱스, 찾지 못하면 -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```

지정된 인덱스에 수학 요소를 컬렉션에 삽입합니다.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | IMathElement가 삽입될 0부터 시작하는 인덱스 |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 삽입할 IMathElement |

### clear() {#clear--}
```
public abstract void clear()
```

컬렉션의 모든 요소를 제거합니다.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public abstract boolean contains(IMathElement item)
```

컬렉션에 특정 값이 포함되어 있는지 확인합니다.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  bool contains = collection.contains(plusElement);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 컬렉션에서 찾을 객체 |

**반환값:**
boolean - 컬렉션에서 항목을 찾으면 true, 그렇지 않으면 false.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```

컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.remove(plusElement);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 컬렉션에서 제거할 객체 |

**반환값:**
boolean - 컬렉션에서 항목이 성공적으로 제거되면 true, 그렇지 않으면 false. 원래 컬렉션에 항목이 없는 경우에도 false를 반환합니다.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

컬렉션의 지정된 인덱스에 있는 요소를 제거합니다.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.removeAt(2);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 요소의 0부터 시작하는 인덱스 |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```

지정된 배열에 복사합니다.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[collection.Count];
>  collection.copyTo(destinationArray, 0);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | 복사할 배열 |
| arrayIndex | int | 복사를 시작할 인덱스 |