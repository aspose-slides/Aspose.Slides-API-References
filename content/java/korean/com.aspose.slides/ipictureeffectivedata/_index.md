---
title: IPictureEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective picture properties.
type: docs
url: /ko/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

실제 그림 속성을 포함하는 불변 객체.

--------------------

이 인터페이스는 [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)와 [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)의 일부로 사용됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getImage()](#getImage--) | 내장된 이미지를 반환합니다. |
| [getLinkPathLong()](#getLinkPathLong--) | 연결된 이미지의 URL을 반환합니다. |
| [getImageTransform()](#getImageTransform--) | 이미지 변환 효과 컬렉션을 반환합니다. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

내장된 이미지를 반환합니다. 읽기 전용 [IPPImage](../../com.aspose.slides/ippimage).

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

연결된 이미지의 URL을 반환합니다. 읽기 전용 String.

**Returns:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```

이미지 변환 효과 컬렉션을 반환합니다. 읽기 전용 [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**Returns:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)