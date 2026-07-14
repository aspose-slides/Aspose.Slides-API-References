---
title: ICustomXmlPartCollection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 맞춤 XML 파트의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icustomxmlpartcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

맞춤 XML 파트의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the element at the specified index. |
| [add(byte[] xmlData)](#add-byte---) | Adds new custom xml part. |
| [add(String xmlString)](#add-java.lang.String-) | Adds new custom xml part. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Adds new custom xml part. |
| [removeAt(int index)](#removeAt-int-) | Removes custom xml part at the specified index. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Removes the first occurrence of a specific object from the collection. |
| [clear()](#clear--) | Removes all items from the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

지정된 인덱스에 있는 요소를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 가져올 요소의 0부터 시작하는 인덱스입니다. |

**반환값:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 지정된 인덱스에 있는 요소입니다.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

새 맞춤 XML 파트를 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlData | byte[] | 추가될 새 파트의 XML 데이터입니다. |

**반환값:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 생성된 맞춤 XML 파트.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

새 맞춤 XML 파트를 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlString | java.lang.String | 추가될 새 파트의 XML 문자열입니다. |

**반환값:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 생성된 맞춤 XML 파트.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```

새 맞춤 XML 파트를 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 추가될 새 파트의 XML 데이터를 포함하는 inputStream입니다. |

**반환값:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 생성된 맞춤 XML 파트.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

지정된 인덱스에 있는 맞춤 XML 파트를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 요소의 0부터 시작하는 인덱스입니다. |
### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```

컬렉션에서 특정 객체의 첫 번째 항목을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | 제거할 맞춤 XML 파트입니다. |

**반환값:**
boolean - 항목이 성공적으로 제거되면 true, 그렇지 않으면 false.
### clear() {#clear--}
```
public abstract void clear()
```

컬렉션의 모든 항목을 제거합니다.