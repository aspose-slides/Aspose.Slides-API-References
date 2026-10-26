---
title: IVbaModuleCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: VBA 프로젝트 모듈의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ivbamodulecollection/
---
**구현된 모든 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

VBA 프로젝트 모듈의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | VBA 프로젝트에 새 빈 모듈을 추가합니다. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```


지정된 인덱스의 요소를 가져옵니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```


VBA 프로젝트에 새 빈 모듈을 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 모듈 이름 |

**반환:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - 추가된 모듈.
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```


컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | 컬렉션에서 제거할 모듈. |