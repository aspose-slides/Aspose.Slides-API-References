---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides for Android용 Java API 레퍼런스
description: 효과 동작에 대한 타이밍 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ibehaviorpropertycollection/
---
**구현된 모든 인터페이스:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

효과 동작에 대한 타이밍 속성을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | 컬렉션에 새 속성을 추가합니다. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | 목록에서 속성 값으로 특정 항목의 인덱스를 결정합니다. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | 지정된 인덱스에 지정된 속성 값을 가진 새 속성을 컬렉션에 삽입합니다. |
| [remove(String propertyValue)](#remove-java.lang.String-) | 컬렉션에서 지정된 속성을 제거합니다. |
| [contains(String propertyValue)](#contains-java.lang.String-) | 특정 값이 [IGenericCollection](../../com.aspose.slides/igenericcollection)에 포함되어 있는지 확인합니다. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

컬렉션에 새 속성을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| propertyValue | java.lang.String | 추가할 속성의 값. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

목록에서 속성 값으로 특정 항목의 인덱스를 결정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| propertyValue | java.lang.String | 속성 값 |

**반환값:**
int - 지정된 값의 속성 인덱스
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

지정된 인덱스에 지정된 속성 값을 가진 새 속성을 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 새 속성을 삽입할 인덱스. |
| propertyValue | java.lang.String | 추가할 속성의 값. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

컬렉션에서 지정된 속성을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| propertyValue | java.lang.String | 제거할 속성의 값. |

**반환값:**
boolean - 속성이 성공적으로 제거되면 true
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)에 특정 값이 포함되어 있는지 확인합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| propertyValue | java.lang.String | [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 찾을 속성 값. |

**반환값:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)에서 propertyValue를 찾으면 true; 그렇지 않으면 false.