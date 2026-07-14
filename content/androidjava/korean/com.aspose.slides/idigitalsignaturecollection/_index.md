---
title: IDigitalSignatureCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 문서에 첨부된 디지털 서명의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/idigitalsignaturecollection/
---
**모든 구현된 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

문서에 첨부된 디지털 서명의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 인덱스로 서명을 반환합니다. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | 컬렉션의 끝에 서명을 추가합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스의 서명을 제거합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 서명을 제거합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```


인덱스로 서명을 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```


컬렉션의 끝에 서명을 추가합니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      signature.setComments("Aspose.Slides digital signing test.");
>      pres.getDigitalSignatures().add(signature);
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | 추가할 서명. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


지정된 인덱스의 서명을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 삭제해야 하는 서명의 인덱스. |

### clear() {#clear--}
```
public abstract void clear()
```


컬렉션에서 모든 서명을 제거합니다.