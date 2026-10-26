---
title: ColorOperationCollection
second_title: Aspose.Slides for Android용 Java API 레퍼런스
description: 컬러 변환 작업의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/coloroperationcollection/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)  
```
public final class ColorOperationCollection implements IColorOperationCollection
```

컬러 변환 작업의 컬렉션을 나타냅니다.

## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | 컬렉션에 포함된 작업 수를 반환합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 작업을 반환하거나 설정합니다. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | 지정된 인덱스에 있는 작업을 반환하거나 설정합니다. |
| [add(int operation, float parameter)](#add-int-float-) | 새 작업을 컬렉션 끝에 추가합니다. |
| [add(int operation)](#add-int-) | 새 작업을 컬렉션 끝에 추가합니다. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | 새 작업을 컬렉션에 삽입합니다. |
| [insert(int position, int operation)](#insert-int-int-) | 새 작업을 컬렉션에 삽입합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션에서 컬러 작업을 제거합니다. |
| [clear()](#clear--) | 모든 컬러 작업을 제거합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java iterator를 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
| [deepClone()](#deepClone--) | ColorOperationCollection 컬렉션의 복사본을 생성합니다. |
| [cloneT()](#cloneT--) | 현재 객체를 복제합니다 |

### size() {#size--}
```
public final int size()
```

컬렉션에 포함된 작업 수를 반환합니다. Read-only int.

**Returns:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

지정된 인덱스에 있는 작업을 반환하거나 설정합니다. Read/write [ColorOperation](../../com.aspose.slides/coloroperation).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**  
[IColorOperation](../../com.aspose.slides/icoloroperation)

### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

지정된 인덱스에 있는 작업을 반환하거나 설정합니다. Read/write [ColorOperation](../../com.aspose.slides/coloroperation).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

새 작업을 컬렉션 끝에 추가합니다.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| operation | int | 작업 유형. |
| parameter | float | 작업의 매개변수. |

**Returns:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - 추가된 연산.

### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

새 작업을 컬렉션 끝에 추가합니다.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| operation | int | 작업 유형. |

**Returns:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - 추가된 연산.

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

새 작업을 컬렉션에 삽입합니다.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | 작업이 삽입될 인덱스. |
| operation | int | 작업 유형. |
| parameter | float | 작업의 매개변수. |

**Returns:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - 삽입된 연산.

### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

새 작업을 컬렉션에 삽입합니다.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | 작업이 삽입될 인덱스. |
| operation | int | 작업 유형. |

**Returns:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - 삽입된 연산.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

컬렉션에서 컬러 작업을 제거합니다.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 제거할 컬러 작업의 인덱스. |

### clear() {#clear--}
```
public final void clear()
```

모든 컬러 작업을 제거합니다.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

전체 컬렉션에 대한 java iterator를 반환합니다.

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - 전체 컬렉션에 대한 java.util.Iterator.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

컬렉션의 모든 요소를 지정된 배열에 복사합니다.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열. |
| index | int | 대상 배열의 시작 인덱스. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

컬렉션에 대한 접근이 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 반환합니다. Read-only boolean.

**Returns:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

동기화 루트를 반환합니다. Read-only Object.

**Returns:**  
java.lang.Object

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

ColorOperationCollection 컬렉션의 복사본을 생성합니다.

**Returns:**  
java.lang.Object - 새 [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) 컬렉션.

### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

현재 객체를 복제합니다.

**Returns:**  
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - 복제본