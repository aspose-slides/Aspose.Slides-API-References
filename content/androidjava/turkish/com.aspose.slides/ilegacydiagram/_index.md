---
title: ILegacyDiagram
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Eski bir diyagram nesnesini temsil eder
type: docs
url: /tr/com.aspose.slides/ilegacydiagram/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Bir eski diyagram nesnesini temsil eder
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Legacy diyagramı düzenlenebilir SmartArt nesnesine dönüştürür. |
| [convertToGroupShape()](#convertToGroupShape--) | Legacy diyagramı düzenlenebilir grup şekline dönüştürür. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

Legacy diyagramı düzenlenebilir SmartArt nesnesine dönüştürür. Oluşturulan SmartArt nesnesi, aynı konumda üst grup şekline eklenir.

**Döndürür:**
[ISmartArt](../../com.aspose.slides/ismartart) - Oluşturulan SmartArt nesnesi.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

Legacy diyagramı düzenlenebilir grup şekline dönüştürür. Oluşturulan GroupShape nesnesi, aynı konumda üst grup şekline eklenir.

**Döndürür:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Oluşturulan GroupShape nesnesi.