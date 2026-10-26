---
title: IFormatSchemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: 효과적인 형식 스키마 속성을 포함하는 불변 객체입니다.
type: docs
url: /ko/com.aspose.slides/iformatschemeeffectivedata/
---```
public interface IFormatSchemeEffectiveData
```

효과적인 형식 스키마 속성을 포함하는 불변 객체입니다.

--------------------

이 인터페이스는 [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)의 일부로 사용됩니다.
## Methods

| Method | Description |
| --- | --- |
| [getFillStyles(Color styleColor)](#getFillStyles-java.awt.Color-) | 테마에서 정의된 채우기 스타일 컬렉션을 반환합니다. |
| [getLineStyles(Color styleColor)](#getLineStyles-java.awt.Color-) | 테마에서 정의된 라인 스타일 컬렉션을 반환합니다. |
| [getEffectStyles(Color styleColor)](#getEffectStyles-java.awt.Color-) | 테마에서 정의된 효과 스타일 컬렉션을 반환합니다. |
| [getBackgroundFillStyles(Color styleColor)](#getBackgroundFillStyles-java.awt.Color-) | 테마에서 정의된 배경 채우기 스타일 컬렉션을 반환합니다. |
### getFillStyles(Color styleColor) {#getFillStyles-java.awt.Color-}
```
public abstract IFillFormatCollectionEffectiveData getFillStyles(Color styleColor)
```

테마에서 정의된 채우기 스타일 컬렉션을 반환합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Returns:**
[IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata) - 유효한 채우기 형식의 컬렉션 [IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata)
### getLineStyles(Color styleColor) {#getLineStyles-java.awt.Color-}
```
public abstract ILineFormatCollectionEffectiveData getLineStyles(Color styleColor)
```

테마에서 정의된 라인 스타일 컬렉션을 반환합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Returns:**
[ILineFormatCollectionEffectiveData](../../com.aspose.slides/ilineformatcollectioneffectivedata) - 유효한 라인 형식의 컬렉션 [ILineFormatCollectionEffectiveData](../../com.aspose.slides/ilineformatcollectioneffectivedata)
### getEffectStyles(Color styleColor) {#getEffectStyles-java.awt.Color-}
```
public abstract IEffectStyleCollectionEffectiveData getEffectStyles(Color styleColor)
```

테마에서 정의된 효과 스타일 컬렉션을 반환합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Returns:**
[IEffectStyleCollectionEffectiveData](../../com.aspose.slides/ieffectstylecollectioneffectivedata) - 유효한 효과 형식의 컬렉션 [IEffectStyleCollectionEffectiveData](../../com.aspose.slides/ieffectstylecollectioneffectivedata)
### getBackgroundFillStyles(Color styleColor) {#getBackgroundFillStyles-java.awt.Color-}
```
public abstract IFillFormatCollectionEffectiveData getBackgroundFillStyles(Color styleColor)
```

테마에서 정의된 배경 채우기 스타일 컬렉션을 반환합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Returns:**
[IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata) - 유효한 배경 채우기 형식의 컬렉션 [IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata)