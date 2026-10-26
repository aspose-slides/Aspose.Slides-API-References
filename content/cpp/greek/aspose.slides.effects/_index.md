---
title: "Aspose::Slides::Effects"
second_title: Aspose.Slides για την αναφορά API C++
description: 
type: docs
weight: 66
url: /el/aspose.slides.effects/
---
## Κλάσεις

| Κλάση | Περιγραφή |
| --- | --- |
| [AlphaBiLevel](./alphabilevel/) | Αντιπροσωπεύει ένα εφέ Alpha Bi-Level. Τιμές Alpha (Διαφάνειας) μικρότερες από το όριο μετατρέπονται σε 0 (εντελώς διαφανείς) και τιμές Alpha μεγαλύτερες ή ίσες με το όριο μετατρέπονται σε 100% (εντελώς αδιαφανείς). |
| [AlphaCeiling](./alphaceiling/) | Αντιπροσωπεύει ένα εφέ Alpha Ceiling. Τιμές Alpha (διαφάνειας) μεγαλύτερες του 0 μετατρέπονται σε 100%. Με άλλα λόγια, ό,τι είναι μερικώς αδιαφανές γίνεται εντελώς αδιαφανές. |
| [AlphaFloor](./alphafloor/) | Αντιπροσωπεύει ένα εφέ Alpha Floor. Τιμές Alpha (διαφάνειας) μικρότερες από 100% μετατρέπονται σε 0. Με άλλα λόγια, ό,τι είναι μερικώς διαφανές γίνεται εντελώς διαφανές. |
| [AlphaInverse](./alphainverse/) | Αντιπροσωπεύει ένα εφέ Alpha Inverse. Τιμές Alpha (διαφάνειας) αντιστρέφονται αφαιρώντας από το 100%. |
| [AlphaModulate](./alphamodulate/) | Αντιπροσωπεύει ένα εφέ Alpha Modulate. Τιμές Alpha (διαφάνειας) του εφέ πολλαπλασιάζονται με ένα σταθερό ποσοστό. Το δοχείο εφέ ορίζει ένα εφέ που περιέχει τιμές Alpha για διαμόρφωση. |
| [AlphaModulateFixed](./alphamodulatefixed/) | Αντιπροσωπεύει ένα εφέ Alpha Modulate Fixed. Τιμές Alpha (διαφάνειας) του εφέ πολλαπλασιάζονται με ένα σταθερό ποσοστό. |
| [AlphaReplace](./alphareplace/) | Αντιπροσωπεύει ένα εφέ Alpha Replace. Τιμές Alpha (διαφάνειας) του εφέ αντικαθίστανται από μια σταθερή τιμή Alpha. |
| [BiLevel](./bilevel/) | Αντιπροσωπεύει ένα εφέ Bi-Level (μαύρο/άσπρο). Τα χρώματα εισόδου των οποίων η λαμπρότητα είναι μικρότερη από την καθορισμένη τιμή ορίου μετατρέπονται σε μαύρο. Τα χρώματα με λαμπρότητα μεγαλύτερη ή ίση με την καθορισμένη τιμή ορίζονται σε λευκό. Οι τιμές Alpha του εφέ δεν επηρεάζονται. |
| [Blur](./blur/) | Αντιπροσωπεύει ένα εφέ [Blur](./blur/) που εφαρμόζεται σε ολόκληρο το σχήμα, συμπεριλαμβανομένης της γεμίσματος. Όλα τα κανάλια χρώματος, συμπεριλαμβανομένου του Alpha, επηρεάζονται. |
| [BrightnessContrast](./brightnesscontrast/) | Αντιπροσωπεύει ένα εφέ [BrightnessContrast](./brightnesscontrast/). Ρυθμίζει τη φωτεινότητα και την αντίθεση. |
| [ColorChange](./colorchange/) | Αντιπροσωπεύει ένα εφέ Color Change. Οι εμφανίσεις του FromColor αντικαθίστανται με αυτές του ToColor. |
| [ColorReplace](./colorreplace/) | Αντιπροσωπεύει ένα εφέ Color Replacement. Ό όλα τα χρώματα του εφέ μετατρέπονται σε ένα σταθερό χρώμα. Οι τιμές Alpha δεν επηρεάζονται. |
| [Duotone](./duotone/) | Αντιπροσωπεύει ένα εφέ [Duotone](./duotone/). Για κάθε pixel, συνδυάζει τα Color1 και Color2 μέσω γραμμικής παρεμβολής για τον καθορισμό του νέου χρώματος του pixel. |
| [EffectFactory](./effectfactory/) | Επιτρέπει τη δημιουργία εφέ. |
| [FillOverlay](./filloverlay/) | Αντιπροσωπεύει ένα εφέ Fill Overlay. Ένα overlay γεμίσματος μπορεί να χρησιμοποιηθεί για να καθορίσει ένα επιπλέον γέμισμα για ένα αντικείμενο και να συνδυάσει τα δύο γεμίσματα. |
| [Glow](./glow/) | Αντιπροσωπεύει ένα εφέ [Glow](./glow/), στο οποίο προστίθεται μια θολή περίγραμμα χρώματος έξω από τις άκρες του αντικειμένου. |
| [GrayScale](./grayscale/) | Αντιπροσωπεύει ένα εφέ Gray Scale. Μετατρέπει όλες τις τιμές χρώματος του εφέ σε απόχρωση του γκρι, ανάλογη της λαμπρότητά τους. Οι τιμές Alpha (διαφάνειας) του εφέ δεν επηρεάζονται. |
| [HSL](./hsl/) | Αντιπροσωπεύει ένα εφέ Hue/Saturation/Luminance. Η απόχρωση, ο κορεσμός και η λαμπρότητα μπορούν να προσαρμοστούν ανάλογα με τις τρέχουσες τιμές τους. |
| [IAlphaBiLevel](./ialphabilevel/) | Αντιπροσωπεύει ένα εφέ Alpha Bi-Level. Τιμές Alpha (Διαφάνειας) μικρότερες από το όριο μετατρέπονται σε 0 (εντελώς διαφανείς) και τιμές Alpha μεγαλύτερες ή ίσες με το όριο μετατρέπονται σε 100% (εντελώς αδιαφανείς). |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ Alpha Bi-Level. Τιμές Alpha (Διαφάνειας) μικρότερες από το όριο μετατρέπονται σε 0 (εντελώς διαφανείς) και τιμές Alpha μεγαλύτερες ή ίσες με το όριο μετατρέπονται σε 100% (εντελώς αδιαφανείς). |
| [IAlphaCeiling](./ialphaceiling/) | Αντιπροσωπεύει ένα εφέ Alpha Ceiling. Τιμές Alpha (διαφάνειας) μεγαλύτερες του 0 μετατρέπονται σε 100%. Με άλλα λόγια, ό,τι είναι μερικώς αδιαφανές γίνεται εντελώς αδιαφανές. |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ Alpha Ceiling. Τιμές Alpha (διαφάνειας) μεγαλύτερες του 0 μετατρέπονται σε 100%. Με άλλα λόγια, ό,τι είναι μερικώς αδιαφανές γίνεται εντελώς αδιαφανές. |
| [IAlphaFloor](./ialphafloor/) | Αντιπροσωπεύει ένα εφέ Alpha Floor. Τιμές Alpha (διαφάνειας) μικρότερες από 100% μετατρέπονται σε 0. Με άλλα λόγια, ό,τι είναι μερικώς διαφανές γίνεται εντελώς διαφανές. |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ Alpha Floor. Τιμές Alpha (διαφάνειας) μικρότερες από 100% μετατρέπονται σε 0. Με άλλα λόγια, ό,τι είναι μερικώς διαφανές γίνεται εντελώς διαφανές. |
| [IAlphaInverse](./ialphainverse/) | Αντιπροσωπεύει ένα εφέ Alpha Inverse. Τιμές Alpha (διαφάνειας) αντιστρέφονται αφαιρώντας από το 100%. |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ Alpha Inverse. Τιμές Alpha (διαφάνειας) αντιστρέφονται αφαιρώντας από το 100%. |
| [IAlphaModulate](./ialphamodulate/) | Αντιπροσωπεύει ένα εφέ Alpha Modulate. Τιμές Alpha (διαφάνειας) του εφέ πολλαπλασιάζονται με ένα σταθερό ποσοστό. Το δοχείο εφέ ορίζει ένα εφέ που περιέχει τιμές Alpha για διαμόρφωση. |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ Alpha Modulate. Τιμές Alpha (διαφάνειας) του εφέ πολλαπλασιάζονται με ένα σταθερό ποσοστό. Το δοχείο εφέ ορίζει ένα εφέ που περιέχει τιμές Alpha για διαμόρφωση. |
| [IAlphaModulateFixed](./ialphamodulatefixed/) | Αντιπροσωπεύει ένα εφέ Alpha Modulate Fixed. Τιμές Alpha (διαφάνειας) του εφέ πολλαπλασιάζονται με ένα σταθερό ποσοστό. |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ Alpha Modulate Fixed. Τιμές Alpha (διαφάνειας) του εφέ πολλαπλασιάζονται με ένα σταθερό ποσοστό. |
| [IAlphaReplace](./ialphareplace/) | Αντιπροσωπεύει τη βασική διεπαφή [IImageTransformOperation](./iimagetransformoperation/). |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ Alpha Replace. |
| [IApplicableEffect](./iapplicableeffect/) |  |
| [IBiLevel](./ibilevel/) | Αντιπροσωπεύει τη βασική διεπαφή [IImageTransformOperation](./iimagetransformoperation/). |
| [IBiLevelEffectiveData](./ibileveleffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ Bi-Level (μαύρο/άσπρο). Τα χρώματα εισόδου των οποίων η λαμπρότητα είναι μικρότερη από την καθορισμένη τιμή ορίου μετατρέπονται σε μαύρο. Τα χρώματα με λαμπρότητα μεγαλύτερη ή ίση με την καθορισμένη τιμή ορίζονται σε λευκό. Οι τιμές Alpha του εφέ δεν επηρεάζονται. |
| [IBlur](./iblur/) | Αντιπροσωπεύει ένα εφέ [Blur](./blur/) που εφαρμόζεται σε ολόκληρο το σχήμα, συμπεριλαμβανομένης της γεμίσματος. Όλα τα κανάλια χρώματος, συμπεριλαμβανομένου του Alpha, επηρεάζονται. |
| [IBlurEffectiveData](./iblureffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ [Blur](./blur/) που εφαρμόζεται σε ολόκληρο το σχήμα, συμπεριλαμβανομένης της γεμίσματος. Όλα τα κανάλια χρώματος, συμπεριλαμβανομένου του Alpha, επηρεάζονται. |
| [IBrightnessContrast](./ibrightnesscontrast/) | Αντιπροσωπεύει ένα εφέ [BrightnessContrast](./brightnesscontrast/). Ρυθμίζει τη φωτεινότητα και την αντίθεση. |
| [IBrightnessContrastEffectiveData](./ibrightnesscontrasteffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ [BrightnessContrast](./brightnesscontrast/). Ρυθμίζει τη φωτεινότητα και την αντίθεση. |
| [IColorChange](./icolorchange/) | Αντιπροσωπεύει ένα εφέ Color Change. Οι εμφανίσεις του FromColor αντικαθίστανται με αυτές του ToColor. |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ Color Change. Οι εμφανίσεις του FromColor αντικαθίστανται με αυτές του ToColor. |
| [IColorReplace](./icolorreplace/) | Αντιπροσωπεύει ένα εφέ Color Replacement. |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ Color Replacement. Ό όλα τα χρώματα του εφέ μετατρέπονται σε ένα σταθερό χρώμα. Οι τιμές Alpha δεν επηρεάζονται. |
| [IDuotone](./iduotone/) | Αντιπροσωπεύει ένα εφέ [Duotone](./duotone/). |
| [IDuotoneEffectiveData](./iduotoneeffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ [Duotone](./duotone/). Για κάθε pixel, συνδυάζει τα clr1 και clr2 μέσω γραμμικής παρεμβολής για τον καθορισμό του νέου χρώματος του pixel. |
| [IEffectEffectiveData](./ieffecteffectivedata/) | Βασική κλάση για αμετάβλητα αντικείμενα, που αντιπροσωπεύουν εφέ. |
| [IEffectFactory](./ieffectfactory/) | Επιτρέπει τη δημιουργία στιγμιότυπων εφέ. |
| [IFillOverlay](./ifilloverlay/) | Αντιπροσωπεύει ένα εφέ Fill Overlay. Ένα overlay γεμίσματος μπορεί να χρησιμοποιηθεί για να καθορίσει ένα επιπλέον γέμισμα για ένα αντικείμενο και να συνδυάσει τα δύο γεμίσματα. |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ Fill Overlay. Ένα overlay γεμίσματος μπορεί να χρησιμοποιηθεί για να καθορίσει ένα επιπλέον γέμισμα για ένα αντικείμενο και να συνδυάσει τα δύο γεμίσματα. |
| [IGlow](./iglow/) | Αντιπροσωπεύει ένα εφέ [Glow](./glow/), στο οποίο προστίθεται μια θολή περίγραμμα χρώματος έξω από τις άκρες του αντικειμένου. |
| [IGlowEffectiveData](./igloweffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ [Glow](./glow/), στο οποίο προστίθεται μια θολή περίγραμμα χρώματος έξω από τις άκρες του αντικειμένου. |
| [IGrayScale](./igrayscale/) | Αντιπροσωπεύει τη διεπαφή [IImageTransformOperation](./iimagetransformoperation/). |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ Gray Scale. Μετατρέπει όλες τις τιμές χρώματος του εφέ σε απόχρωση του γκρι, ανάλογη της λαμπρότητά τους. Οι τιμές Alpha (διαφάνειας) του εφέ δεν επηρεάζονται. |
| [IHSL](./ihsl/) | Αντιπροσωπεύει ένα εφέ Hue/Saturation/Luminance. Η απόχρωση, ο κορεσμός και η λαμπρότητα μπορούν να προσαρμοστούν ανάλογα με τις τρέχουσες τιμές τους. |
| [IHSLEffectiveData](./ihsleffectivedata/) | Αντιπροσωπεύει ένα εφέ Hue/Saturation/Luminance. Η απόχρωση, ο κορεσμός και η λαμπρότητα μπορούν να προσαρμοστούν ανάλογα με τις τρέχουσες τιμές τους. |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει μια συλλογή μόνο για ανάγνωση από επιδραστικά εφέ μετασχηματισμού εικόνας. |
| [IImageTransformOperation](./iimagetransformoperation/) | Αντιπροσωπεύει αφηρημένο εφέ μετασχηματισμού εικόνας. |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection/) | Αντιπροσωπεύει μια συλλογή εφέ που εφαρμόζονται σε μια εικόνα. |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory/) | Επιτρέπει τη δημιουργία στιγμιότυπων εφέ εικόνας. |
| [IInnerShadow](./iinnershadow/) | Αντιπροσωπεύει ένα εφέ εσωτερικής σκιάς. |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ εσωτερικής σκιάς. |
| [ILuminance](./iluminance/) | Αντιπροσωπεύει ένα εφέ [Luminance](./luminance/). Η φωτεινότητα μετατοπίζει γραμμικά όλα τα χρώματα προς το λευκό ή το μαύρο. Η αντίθεση κλιμακώνει όλα τα χρώματα ώστε να είναι πιο κοντά ή πιο μακριά μεταξύ τους. |
| [ILuminanceEffectiveData](./iluminanceeffectivedata/) | Αντιπροσωπεύει ένα εφέ [Luminance](./luminance/). Η φωτεινότητα μετατοπίζει γραμμικά όλα τα χρώματα προς το λευκό ή το μαύρο. Η αντίθεση κλιμακώνει όλα τα χρώματα ώστε να είναι πιο κοντά ή πιο μακριά μεταξύ τους. |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει μια συλλογή μόνο για ανάγνωση από επιδραστικά εφέ μετασχηματισμού εικόνας. |
| [ImageTransformOperation](./imagetransformoperation/) | Αντιπροσωπεύει αφηρημένο εφέ μετασχηματισμού εικόνας. |
| [ImageTransformOperationCollection](./imagetransformoperationcollection/) | Αντιπροσωπεύει μια συλλογή εφέ που εφαρμόζονται σε μια εικόνα. |
| [ImageTransformOperationFactory](./imagetransformoperationfactory/) | Επιτρέπει τη δημιουργία λειτουργιών μετασχηματισμού εικόνας. |
| [InnerShadow](./innershadow/) | Αντιπροσωπεύει ένα εφέ Inner Shadow. |
| [IOuterShadow](./ioutershadow/) | Αντιπροσωπεύει ένα εφέ Outer Shadow. |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ Outer Shadow. |
| [IPresetShadow](./ipresetshadow/) | Αντιπροσωπεύει ένα εφέ Preset Shadow. |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ Preset Shadow. |
| [IReflection](./ireflection/) | Αντιπροσωπεύει ένα εφέ αντανάκλασης. |
| [IReflectionEffectiveData](./ireflectioneffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ [Reflection](./reflection/). |
| [ISoftEdge](./isoftedge/) | Αντιπροσωπεύει ένα εφέ Soft Edge. Οι άκρες του σχήματος θολώνουν, ενώ το γέμισμα δεν επηρεάζεται. |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ soft edge. Οι άκρες του σχήματος θολώνουν, ενώ το γέμισμα δεν επηρεάζεται. |
| [ITint](./itint/) | Αντιπροσωπεύει ένα εφέ [Tint](./tint/). Μετατοπίζει τις τιμές χρώματος του εφέ προς ή μακριά από την απόχρωση κατά το καθορισμένο ποσό. |
| [ITintEffectiveData](./itinteffectivedata/) | Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ [Tint](./tint/). Μετατοπίζει τις τιμές χρώματος του εφέ προς ή μακριά από την απόχρωση κατά το καθορισμένο ποσό. |
| [IVisualEffect](./ivisualeffect/) |  |
| [Luminance](./luminance/) | Αντιπροσωπεύει ένα εφέ [Luminance](./luminance/). Η φωτεινότητα μετατοπίζει γραμμικά όλα τα χρώματα προς το λευκό ή το μαύρο. Η αντίθεση κλιμακώνει όλα τα χρώματα ώστε να είναι πιο κοντά ή πιο μακριά μεταξύ τους. |
| [OuterShadow](./outershadow/) | Αντιπροσωπεύει ένα εφέ Outer Shadow. |
| [PresetShadow](./presetshadow/) | Αντιπροσωπεύει ένα εφέ Preset Shadow. |
| [Reflection](./reflection/) | Αντιπροσωπεύει ένα εφέ [Reflection](./reflection/). |
| [SoftEdge](./softedge/) | Αντιπροσωπεύει ένα εφέ soft edge. Οι άκρες του σχήματος θολώνουν, ενώ το γέμισμα δεν επηρεάζεται. |
| [Tint](./tint/) | Αντιπροσωπεύει ένα εφέ [Tint](./tint/). Μετατοπίζει τις τιμές χρώματος του εφέ προς ή μακριά από την απόχρωση κατά το καθορισμένο ποσό. |