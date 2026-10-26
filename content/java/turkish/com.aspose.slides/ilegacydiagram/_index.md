---
title: ILegacyDiagram
second_title: Aspose.Slides for Java API Referansı
description: Eski bir diyagram nesnesini temsil eder
type: docs
url: /tr/com.aspose.slides/ilegacydiagram/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Eski bir diyagram nesnesini temsil eder
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Eski digramı düzenlenebilir SmartArt nesnesine dönüştürür. |
| [convertToGroupShape()](#convertToGroupShape--) | Eski digramı düzenlenebilir grup şekline dönüştürür. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```


Eski digramı düzenlenebilir SmartArt nesnesine dönüştürür. Oluşturulan SmartArt nesnesi aynı konumda üst grup şekline eklenir.

**Döndürür:**
[ISmartArt](../../com.aspose.slides/ismartart) - Oluşturulan SmartArt nesnesi.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```


Eski digramı düzenlenebilir grup şekline dönüştürür. Oluşturulan GroupShape nesnesi aynı konumda üst grup şekline eklenir.

**Döndürür:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Oluşturulan GroupShape nesnesi.