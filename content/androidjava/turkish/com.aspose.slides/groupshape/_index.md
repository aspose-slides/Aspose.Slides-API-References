---
title: GroupShape
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Bir slayttaki şekil grubunu temsil eder.
type: docs
url: /tr/com.aspose.slides/groupshape/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

Bir slayttaki şekil grubunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Bir şekil için çizgi biçimleme özelliklerini içeren LineFormat nesnesini döndürür. |
| [getGroupShapeLock()](#getGroupShapeLock--) | Şeklin kilitlerini döndürür. |
| [getShapes()](#getShapes--) | Grup içindeki şekillerin koleksiyonunu döndürür. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Bir şekil için çizgi biçimleme özelliklerini içeren LineFormat nesnesini döndürür. Not: GroupShape nesneleri için null döndürür çünkü çizgi özellikleri yoktur. Salt-okunur [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```

Şeklin kilitlerini döndürür. Salt-okunur [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Döndürür:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Grup içindeki şekillerin koleksiyonunu döndürür. Salt-okunur [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Döndürür:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)