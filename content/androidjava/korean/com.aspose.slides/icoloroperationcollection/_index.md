---
title: IColorOperationCollection
second_title: Aspose.Slides for Android용 Java API 레퍼런스
description: 색상 변환 작업의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icoloroperationcollection/
---
**구현된 모든 인터페이스:**  
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

색상 변환 작업의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에서 작업을 반환하거나 설정합니다. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | 지정된 인덱스에서 작업을 반환하거나 설정합니다. |
| [add(int operation, float parameter)](#add-int-float-) | 새 작업을 컬렉션의 끝에 추가합니다. |
| [add(int operation)](#add-int-) | 새 작업을 컬렉션의 끝에 추가합니다. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | 새 작업을 컬렉션에 삽입합니다. |
| [insert(int position, int operation)](#insert-int-int-) | 새 작업을 컬렉션에 삽입합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션에서 색상 작업을 제거합니다. |
| [clear()](#clear--) | 모든 색상 작업을 제거합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

지정된 인덱스에서 작업을 반환하거나 설정합니다. 읽기/쓰기 [IColorOperation](../../com.aspose.slides/icoloroperation).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

지정된 인덱스에서 작업을 반환하거나 설정합니다. 읽기/쓰기 [IColorOperation](../../com.aspose.slides/icoloroperation).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

새 작업을 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| operation | int | 작업 유형. |
| parameter | float | 작업의 매개변수. |

**반환:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 추가된 작업.
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

새 작업을 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| operation | int | 작업 유형. |

**반환:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 추가된 작업.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

새 작업을 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| position | int | 작업이 삽입될 인덱스. |
| operation | int | 작업 유형. |
| parameter | float | 작업의 매개변수. |

**반환:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 삽입된 작업.
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

새 작업을 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| position | int | 작업이 삽입될 인덱스. |
| operation | int | 작업 유형. |

**반환:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 삽입된 작업.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

컬렉션에서 색상 작업을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 제거할 색상 작업의 인덱스. |

### clear() {#clear--}
```
public abstract void clear()
```

모든 색상 작업을 제거합니다.