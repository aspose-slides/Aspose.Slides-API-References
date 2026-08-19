---
title: ILightRigEffectiveData
second_title: Aspose.Slides برای Java API Reference
description: شیء غیرقابل تغییر که شامل ویژگی‌های مؤثر light rig است.
type: docs
url: /fa/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

شیء غیرقابل تغییر که شامل ویژگی‌های مؤثر light rig است.

--------------------

این رابط به عنوان بخشی از [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) استفاده می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getDirection()](#getDirection--) | جهت نور. |
| [getLightType()](#getLightType--) | یک نور پیش‌تنظیم راست که می‌تواند بر روی یک شکل اعمال شود. |
| [getRotation()](#getRotation--) | یک چرخش از طریق استفاده از مختصات عرض، مختصات طول، و دوران حول محور به عنوان مختصات عرض و طول تعریف می‌شود. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

جهت نور. فقط‌خواندنی [LightingDirection](../../com.aspose.slides/lightingdirection).

**باز می‌گردد:**  
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

یک نور پیش‌تنظیم راست که می‌تواند بر روی یک شکل اعمال شود. light rig مجموعه‌ای از نورها را که به‌صورت خاصی نسبت به صحنه 3D جهت‌دار هستند، نشان می‌دهد. فقط‌خواندنی [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**باز می‌گردد:**  
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

یک چرخش از طریق استفاده از مختصات عرض، مختصات طول، و دوران حول محور به عنوان مختصات عرض و طول تعریف می‌شود. اولین عنصر در آرایه بازگشتی - عرض، دومین - طول، سومین - دوران.

**باز می‌گردد:**  
float[] - مختصات چرخش به عنوان float[]