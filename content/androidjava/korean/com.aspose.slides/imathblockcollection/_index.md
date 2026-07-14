---
title: IMathBlockCollection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 수학 블록 IMathBlock의 컬렉션
type: docs
url: /ko/com.aspose.slides/imathblockcollection/
---
**구현된 모든 인터페이스:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

수학 블록 컬렉션 (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | 컬렉션의 끝에 IMathBlock을 추가합니다. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | 지정된 인덱스에 컬렉션에 IMathBlock을 삽입합니다. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션에서 지정된 인덱스의 항목을 제거합니다. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | 컬렉션에 특정 값이 포함되어 있는지 확인합니다. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | 컬렉션에서 특정 IMathBlock의 인덱스를 반환합니다. |
| [getCount()](#getCount--) | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 항목을 가져옵니다. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | 지정된 인덱스의 항목을 가져옵니다. |
| [clear()](#clear--) | 컬렉션의 모든 요소를 제거합니다. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

컬렉션의 끝에 IMathBlock을 추가합니다.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | 컬렉션의 끝에 추가될 수학 블록 |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

지정된 인덱스에 컬렉션에 IMathBlock을 삽입합니다.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 항목을 삽입해야 하는 0부터 시작하는 인덱스. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | 삽입할 IMathBlock |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | 컬렉션에서 제거할 객체. |

**반환값:**
boolean - 컬렉션에서 항목이 성공적으로 제거되면 true, 그렇지 않으면 false. 원래 컬렉션에 항목이 없을 경우에도 false를 반환합니다.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

컬렉션에서 지정된 인덱스의 항목을 제거합니다.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 제거할 항목의 0부터 시작하는 인덱스. |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

컬렉션에 특정 값이 포함되어 있는지 확인합니다.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | 컬렉션에서 찾을 객체. |

**반환값:**
boolean - 항목이 컬렉션에 있으면 true, 그렇지 않으면 false.

### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

컬렉션에서 특정 IMathBlock의 인덱스를 반환합니다.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | 컬렉션에서 찾을 항목. |

**반환값:**
int - 컬렉션에서 항목이 발견되면 해당 인덱스를 반환하고, 그렇지 않으면 -1을 반환합니다.

### getCount() {#getCount--}
```
public abstract int getCount()
```

컬렉션에 실제로 포함된 요소 수를 가져옵니다. 읽기 전용 int.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**반환값:**
int

### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```

지정된 인덱스의 항목을 가져옵니다. 읽기 전용 [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 가져올 항목의 0부터 시작하는 인덱스. |

**반환값:**
[IMathBlock](../../com.aspose.slides/imathblock) - 수학 텍스트 블록.

### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

지정된 인덱스의 항목을 가져옵니다. 읽기 전용 [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 설정할 항목의 0부터 시작하는 인덱스. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | 수학 텍스트 블록.

### clear() {#clear--}
```
public abstract void clear()
```

컬렉션의 모든 요소를 제거합니다.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```