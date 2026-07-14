---
title: IChartWall
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل الجدران في المخططات ثلاثية الأبعاد.
type: docs
url: /ar/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

يمثل الجدران في المخططات ثلاثية الأبعاد.
## الطرق

| Method | Description |
| --- | --- |
| [getThickness()](#getThickness--) | تُرجع أو تُعيّن سمك الجدران كنسبة مئوية من أكبر بُعد لحجم المخطط. |
| [setThickness(int value)](#setThickness-int-) | تُرجع أو تُعيّن سمك الجدران كنسبة مئوية من أكبر بُعد لحجم المخطط. |
| [getFormat()](#getFormat--) | تُرجع تعبئة الجدار، الخط، التأثير، الأنماط ثلاثية الأبعاد. |
| [getPictureType()](#getPictureType--) | تُرجع أو تُعيّن نوع الصورة. |
| [setPictureType(int value)](#setPictureType-int-) | تُرجع أو تُعيّن نوع الصورة. |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```


تُرجع أو تُعيّن سمك الجدران كنسبة مئوية من أكبر بُعد لحجم المخطط. قراءة/كتابة int.

**القيمة المرجعة:**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```


تُرجع أو تُعيّن سمك الجدران كنسبة مئوية من أكبر بُعد لحجم المخطط. قراءة/كتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


تُرجع تعبئة الجدار، الخط، التأثير، الأنماط ثلاثية الأبعاد. قراءة فقط [IFormat](../../com.aspose.slides/iformat).

**القيمة المرجعة:**
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```


تُرجع أو تُعيّن نوع الصورة. قراءة/كتابة [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**القيمة المرجعة:**
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```


تُرجع أو تُعيّن نوع الصورة. قراءة/كتابة [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |