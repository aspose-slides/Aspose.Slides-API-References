---
title: CustomLineCap()
second_title: Αναφορά API του Aspose.Slides για C++
description: Δημιουργεί ένα νέο αντικείμενο της κλάσης CustomLineCap που αντιπροσωπεύει μια προσαρμοσμένη άκρη γραμμής ορισμένη από τον χρήστη με τις καθορισμένες ιδιότητες.
type: docs
weight: 1
url: /el/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) κατασκευαστής

Δημιουργεί ένα νέο αντικείμενο της κλάσης [CustomLineCap](../) που αντιπροσωπεύει μια προσαρμοσμένη άκρη γραμμής με τις καθορισμένες ιδιότητες.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Καθορίζει ένα γέμισμα για την προσαρμοσμένη άκρη |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Καθορίζει ένα περίγραμμα της προσαρμοσμένης άκρης |
| baseCap | [LineCap](../../linecap/) | Η βασική άκρη γραμμής από την οποία δημιουργείται η προσαρμοσμένη άκρη |
| baseInset | **float** | Καθορίζει την απόσταση μεταξύ της γραμμής και της άκρης |

## Δείτε επίσης

* Απαρίθμηση [LineCap](../../linecap/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [GraphicsPath](../../graphicspath/)
* Κλάση [CustomLineCap](../)
* Χώρος ονομάτων [System::Drawing::Drawing2D](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)