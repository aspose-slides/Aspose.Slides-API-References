---
title: SetClip()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει την περιοχή αποκοπής της επιφάνειας σχεδίασης που αντιπροσωπεύεται από το τρέχον αντικείμενο Graphics στο αποτέλεσμα της καθορισμένης λειτουργίας που συνδυάζει την τρέχουσα περιοχή αποκοπής και τη συγκεκριμένη περιοχή.
type: docs
weight: 690
url: /el/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) μέθοδος


Ορίζει την περιοχή αποκοπής της επιφάνειας σχεδίασης που αντιπροσωπεύεται από το τρέχον αντικείμενο [Graphics](../) στο αποτέλεσμα της καθορισμένης λειτουργίας που συνδυάζει την τρέχουσα περιοχή αποκοπής και τη συγκεκριμένη περιοχή.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | Καθορίζει μια περιοχή προς συνδυασμό |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Καθορίζει τη λειτουργία συνδυασμού |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) μέθοδος


Ορίζει την περιοχή αποκοπής της επιφάνειας σχεδίασης που αντιπροσωπεύεται από το τρέχον αντικείμενο [Graphics](../) στο αποτέλεσμα της καθορισμένης λειτουργίας που συνδυάζει την τρέχουσα περιοχή αποκοπής και τη συγκεκριμένη περιοχή.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Καθορίζει μια περιοχή προς συνδυασμό |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Καθορίζει τη λειτουργία συνδυασμού |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) μέθοδος


Ορίζει την περιοχή αποκοπής της επιφάνειας σχεδίασης που αντιπροσωπεύεται από το τρέχον αντικείμενο [Graphics](../) στο αποτέλεσμα της καθορισμένης λειτουργίας που συνδυάζει την τρέχουσα περιοχή αποκοπής και τη συγκεκριμένη περιοχή.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Καθορίζει μια περιοχή προς συνδυασμό |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Καθορίζει τη λειτουργία συνδυασμού |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) μέθοδος


ΔΕΝ ΥΠΑΡΧΕΙ ΥΛΟΠΟΙΗΣΗ.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) μέθοδος


Ορίζει την περιοχή αποκοπής της επιφάνειας σχεδίασης που αντιπροσωπεύεται από το τρέχον αντικείμενο [Graphics](../) στο αποτέλεσμα της καθορισμένης λειτουργίας που συνδυάζει την τρέχουσα περιοχή αποκοπής και τη περιοχή που καθορίζεται από μια διαδρομή γραφικών.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Καθορίζει μια περιοχή προς συνδυασμό |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Καθορίζει τη λειτουργία συνδυασμού |

## Δείτε επίσης

* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../../region/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)