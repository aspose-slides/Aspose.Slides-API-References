---
title: ILegacyDiagram
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αναπαριστά ένα legacy diagram object
type: docs
url: /el/com.aspose.slides/ilegacydiagram/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Αναπαριστά ένα legacy diagram object

## Μέθοδοι

| Method | Description |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Μετατρέπει το legacy digram σε επεξεργάσιμο SmartArt object. |
| [convertToGroupShape()](#convertToGroupShape--) | Μετατρέπει το legacy digram σε επεξεργάσιμο group shape. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

Μετατρέπει το legacy digram σε επεξεργάσιμο SmartArt object. Το δημιουργημένο SmartArt object προστίθεται στο γονικό group shape στην ίδια θέση.

**Επιστρέφει:**
[ISmartArt](../../com.aspose.slides/ismartart) - Created SmartArt object.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

Μετατρέπει το legacy digram σε επεξεργάσιμο group shape. Το δημιουργημένο GroupShape object προστίθεται στο γονικό group shape στην ίδια θέση.

**Επιστρέφει:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Created GroupShape object.