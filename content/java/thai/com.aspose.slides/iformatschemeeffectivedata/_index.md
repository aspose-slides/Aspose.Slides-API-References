---
title: IFormatSchemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: วัตถุที่ไม่เปลี่ยนแปลงซึ่งมีคุณสมบัติโครงร่างรูปแบบที่มีผล.
type: docs
url: /th/com.aspose.slides/iformatschemeeffectivedata/
---```
public interface IFormatSchemeEffectiveData
```

วัตถุที่ไม่เปลี่ยนแปลงซึ่งมีคุณสมบัติโครงร่างรูปแบบที่มีผล.

--------------------

This interface is used as a part of [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFillStyles(Color styleColor)](#getFillStyles-java.awt.Color-) | ส่งคืนคอลเลกชันของสไตล์การเติมที่กำหนดโดยธีม. |
| [getLineStyles(Color styleColor)](#getLineStyles-java.awt.Color-) | ส่งคืนคอลเลกชันของสไตล์เส้นที่กำหนดโดยธีม. |
| [getEffectStyles(Color styleColor)](#getEffectStyles-java.awt.Color-) | ส่งคืนคอลเลกชันของสไตล์เอฟเฟกต์ที่กำหนดโดยธีม. |
| [getBackgroundFillStyles(Color styleColor)](#getBackgroundFillStyles-java.awt.Color-) | ส่งคืนคอลเลกชันของสไตล์การเติมพื้นหลังที่กำหนดโดยธีม. |
### getFillStyles(Color styleColor) {#getFillStyles-java.awt.Color-}
```
public abstract IFillFormatCollectionEffectiveData getFillStyles(Color styleColor)
```

ส่งคืนคอลเลกชันของสไตล์การเติมที่กำหนดโดยธีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**ค่าที่ส่งคืน:**
[IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata) - คอลเลกชันของรูปแบบการเติมที่มีผล [IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata)
### getLineStyles(Color styleColor) {#getLineStyles-java.awt.Color-}
```
public abstract ILineFormatCollectionEffectiveData getLineStyles(Color styleColor)
```

ส่งคืนคอลเลกชันของสไตล์เส้นที่กำหนดโดยธีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**ค่าที่ส่งคืน:**
[ILineFormatCollectionEffectiveData](../../com.aspose.slides/ilineformatcollectioneffectivedata) - คอลเลกชันของรูปแบบเส้นที่มีผล [ILineFormatCollectionEffectiveData](../../com.aspose.slides/ilineformatcollectioneffectivedata)
### getEffectStyles(Color styleColor) {#getEffectStyles-java.awt.Color-}
```
public abstract IEffectStyleCollectionEffectiveData getEffectStyles(Color styleColor)
```

ส่งคืนคอลเลกชันของสไตล์เอฟเฟกต์ที่กำหนดโดยธีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**ค่าที่ส่งคืน:**
[IEffectStyleCollectionEffectiveData](../../com.aspose.slides/ieffectstylecollectioneffectivedata) - คอลเลกชันของรูปแบบเอฟเฟกต์ที่มีผล [IEffectStyleCollectionEffectiveData](../../com.aspose.slides/ieffectstylecollectioneffectivedata)
### getBackgroundFillStyles(Color styleColor) {#getBackgroundFillStyles-java.awt.Color-}
```
public abstract IFillFormatCollectionEffectiveData getBackgroundFillStyles(Color styleColor)
```

ส่งคืนคอลเลกชันของสไตล์การเติมพื้นหลังที่กำหนดโดยธีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**ค่าที่ส่งคืน:**
[IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata) - คอลเลกชันของรูปแบบการเติมพื้นหลังที่มีผล [IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata)