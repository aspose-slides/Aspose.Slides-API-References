---
title: ILegacyDiagram
second_title: Aspose.Slides για Java API Reference
description: Αντιπροσωπεύει ένα αντικείμενο παλαιού διαγράμματος
type: docs
url: /el/com.aspose.slides/ilegacydiagram/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Αντιπροσωπεύει ένα αντικείμενο παλαιού διαγράμματος
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Μετατρέπει το παλαιό διαγράμμα σε επεξεργάσιμο αντικείμενο SmartArt. |
| [convertToGroupShape()](#convertToGroupShape--) | Μετατρέπει το παλαιό διαγράμμα σε επεξεργάσιμο group shape. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```


Μετατρέπει το παλαιό διαγράμμα σε επεξεργάσιμο αντικείμενο SmartArt. Το δημιουργημένο αντικείμενο SmartArt προστίθεται στο γονικό group shape στην ίδια θέση.

**Επιστρέφει:**
[ISmartArt](../../com.aspose.slides/ismartart) - Δημιουργημένο αντικείμενο SmartArt.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```


Μετατρέπει το παλαιό διαγράμμα σε επεξεργάσιμο group shape. Το δημιουργημένο αντικείμενο GroupShape προστίθεται στο γονικό group shape στην ίδια θέση.

**Επιστρέφει:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Δημιουργημένο αντικείμενο GroupShape.