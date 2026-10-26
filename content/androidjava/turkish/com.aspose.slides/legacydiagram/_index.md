---
title: LegacyDiagram
second_title: Aspose.Slides for Android via Java API Referansı
description: Eski bir diyagram nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/legacydiagram/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

Eski bir diyagram nesnesini temsil eder.
## Yöntemler

| Method | Description |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Converts legacy digram to editable SmartArt object. |
| [convertToGroupShape()](#convertToGroupShape--) | Converts legacy digram to editable group shape. |
### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```


Eski diyagramı düzenlenebilir SmartArt nesnesine dönüştürür. Oluşturulan SmartArt nesnesi aynı konumdaki üst grup şekline eklenir.

**Döndürür:**
[ISmartArt](../../com.aspose.slides/ismartart) - Oluşturulan SmartArt nesnesi.
### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```


Eski diyagramı düzenlenebilir grup şekline dönüştürür. Oluşturulan GroupShape nesnesi aynı konumdaki üst grup şekline eklenir.

**Döndürür:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Oluşturulan GroupShape nesnesi.