---
title: IPictureEffectiveData
second_title: Aspose.Slides Android용 Java API 참조
description: 효과적인 그림 속성을 포함하는 불변 객체.
type: docs
url: /ko/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

효과적인 그림 속성을 포함하는 불변 객체.

--------------------

이 인터페이스는 [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) 및 [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)의 일부로 사용됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getImage()](#getImage--) | 내장된 이미지를 반환합니다. |
| [getLinkPathLong()](#getLinkPathLong--) | 링크된 이미지의 URL을 반환합니다. |
| [getImageTransform()](#getImageTransform--) | 이미지 변환 효과 컬렉션을 반환합니다. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

내장된 이미지를 반환합니다. 읽기 전용 [IPPImage](../../com.aspose.slides/ippimage).

**반환:**  
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

링크된 이미지의 URL을 반환합니다. 읽기 전용 String.

**반환:**  
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```

이미지 변환 효과 컬렉션을 반환합니다. 읽기 전용 [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**반환:**  
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)