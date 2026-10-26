---
title: IColorOperationCollection
second_title: Aspose.Slides for Java API 레퍼런스
description: 컬러 변환 작업의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icoloroperationcollection/
---
**모든 구현된 인터페이스:**  
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

컬러 변환 작업의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에서 연산을 반환하거나 설정합니다. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | 지정된 인덱스에서 연산을 반환하거나 설정합니다. |
| [add(int operation, float parameter)](#add-int-float-) | 컬렉션 끝에 새 연산을 추가합니다. |
| [add(int operation)](#add-int-) | 컬렉션 끝에 새 연산을 추가합니다. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | 컬렉션에 새 연산을 삽입합니다. |
| [insert(int position, int operation)](#insert-int-int-) | 컬렉션에 새 연산을 삽입합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션에서 색 연산을 제거합니다. |
| [clear()](#clear--) | 모든 색 연산을 제거합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

지정된 인덱스에서 연산을 반환하거나 설정합니다. 읽기/쓰기 [IColorOperation](../../com.aspose.slides/icoloroperation).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

지정된 인덱스에서 연산을 반환하거나 설정합니다. 읽기/쓰기 [IColorOperation](../../com.aspose.slides/icoloroperation).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

컬렉션 끝에 새 연산을 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| operation | int | 연산 유형. |
| parameter | float | 연산 매개변수. |

**반환값:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 추가된 연산.
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

컬렉션 끝에 새 연산을 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| operation | int | 연산 유형. |

**반환값:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 추가된 연산.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

컬렉션에 새 연산을 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | int | 연산이 삽입될 인덱스. |
| operation | int | 연산 유형. |
| parameter | float | 연산 매개변수. |

**반환값:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 삽입된 연산.
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

컬렉션에 새 연산을 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | int | 연산이 삽입될 인덱스. |
| operation | int | 연산 유형. |

**반환값:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 삽입된 연산.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

컬렉션에서 색 연산을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 색 연산의 인덱스. |

### clear() {#clear--}
```
public abstract void clear()
```

모든 색 연산을 제거합니다.