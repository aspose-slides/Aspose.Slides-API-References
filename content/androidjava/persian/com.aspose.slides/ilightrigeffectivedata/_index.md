---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective light rig properties.
type: docs
url: /fa/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

شیء غیرقابل تغییر که خصوصیات مؤثر لایت‌ریگ را شامل می‌شود.

--------------------

این رابط به‌عنوان بخشی از [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) استفاده می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getDirection()](#getDirection--) | جهت نور. |
| [getLightType()](#getLightType--) | نمایانگر نور پیش‌تنظیم سمت راست است که می‌تواند به شکلی اعمال شود. |
| [getRotation()](#getRotation--) | چرخش از طریق استفاده از مختصات عرض جغرافیایی، مختصات طول جغرافیایی و یک دوران حول محور به‌عنوان مختصات عرض و طول تعریف می‌شود. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

جهت نور. فقط-خواندنی [LightingDirection](../../com.aspose.slides/lightingdirection).

**مقدار بازگشتی:**  
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

نمایانگر نور پیش‌تنظیم سمت راست است که می‌تواند به شکلی اعمال شود. لایت ریگ گروهی از نورها را نشان می‌دهد که نسبت به صحنهٔ سه‌بعدی به‌صورت خاصی جهت‌دار می‌شوند. فقط-خواندنی [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**مقدار بازگشتی:**  
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

چرخش از طریق استفاده از مختصات عرض جغرافیایی، مختصات طول جغرافیایی و یک دوران حول محور به‌عنوان مختصات عرض و طول تعریف می‌شود. اولین عنصر در آرایهٔ بازگشتی – عرض، دوم – طول، سوم – دوران.

**مقدار بازگشتی:**  
float[] - مختصات چرخش به‌صورت float[]