---
title: FontsManager
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs
url: /el/aspose.slides/fontsmanager/
---
## FontsManager κλάση

 Διαχειρίζεται τις γραμματοσειρές σε όλη την παρουσίαση.

### addEmbeddedFont {#addEmbeddedFont}

| Όνομα | Περιγραφή |
| --- | --- |
| addEmbeddedFont ([FontData](../fontdata), int) | Προσθέτει την ενσωματωμένη γραμματοσειρά |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Μπορεί να εκτιναχθεί ArgumentException εάν τα δεδομένα γραμματοσειράς είναι null ή αυτή η γραμματοσειρά είναι ήδη ενσωματωμένη. Να έχετε υπόψη ότι όταν αντιγράφετε γραμματοσειρές, οι περισσότερες είναι πνευματικά δικαιώματα. Πρώτα εντοπίστε την άδεια μιας γραμματοσειράς εκ των προτέρων και βεβαιωθείτε ότι μπορεί να μεταφερθεί ελεύθερα σε άλλη μηχανή. |


---


### addEmbeddedFont {#addEmbeddedFont}

| Όνομα | Περιγραφή |
| --- | --- |
| addEmbeddedFont (byte[], int) | Προσθέτει την ενσωματωμένη γραμματοσειρά |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Μπορεί να εκτιναχθεί ArgumentException εάν τα δεδομένα γραμματοσειράς είναι null ή αυτή η γραμματοσειρά είναι ήδη ενσωματωμένη. Να έχετε υπόψη ότι όταν αντιγράφετε γραμματοσειρές, οι περισσότερες είναι πνευματικά δικαιώματα. Πρώτα εντοπίστε την άδεια μιας γραμματοσειράς εκ των προτέρων και βεβαιωθείτε ότι μπορεί να μεταφερθεί ελεύθερα σε άλλη μηχανή. |


---


### getEmbeddedFonts {#getEmbeddedFonts}

| Όνομα | Περιγραφή |
| --- | --- |
| getEmbeddedFonts () | Επιστρέφει τις γραμματοσειρές που έχουν ενσωματωθεί στην παρουσίαση |

 **Επιστρέφει:**
[FontData](../fontdata)


---


### getFontBytes {#getFontBytes}

| Όνομα | Περιγραφή |
| --- | --- |
| getFontBytes ([FontData](../fontdata), int) | Ανακτά τον πίνακα byte που αντιπροσωπεύει τα δεδομένα γραμματοσειράς για ένα συγκεκριμένο στυλ γραμματοσειράς και δεδομένα γραμματοσειράς. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontData | [FontData](../fontdata) | Το αντικείμενο δεδομένων γραμματοσειράς που περιέχει τις πληροφορίες για τη γραμματοσειρά IFontData. |
| fontStyle | int | Το στυλ της γραμματοσειράς για το οποίο πρέπει να ανακτηθούν τα δεδομένα FontStyleType. |

 **Επιστρέφει:**
byte


---


### getFontEmbeddingLevel {#getFontEmbeddingLevel}

| Όνομα | Περιγραφή |
| --- | --- |
| getFontEmbeddingLevel (byte[], String) | Καθορίζει το επίπεδο ενσωμάτωσης μιας γραμματοσειράς από τον δεδομένο πίνακα byte και το όνομα γραμματοσειράς. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontBytes | byte[] | Ο πίνακας byte που περιέχει τα δεδομένα της γραμματοσειράς. |
| fontName | String | Το όνομα της γραμματοσειράς. |

 **Επιστρέφει:**
int

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentNullException | Εκτιναγείται όταν {@code fontBytes} είναι null. |


---


### getFontFallBackRulesCollection {#getFontFallBackRulesCollection}

| Όνομα | Περιγραφή |
| --- | --- |
| getFontFallBackRulesCollection () | Αντιπροσωπεύει τη συλλογή κανόνων FontFallBack ενός χρήστη για τη διαχείριση συλλογών γραμματοσειρών για σωστές αντικαταστάσεις με τη λειτουργία fallback. Ανάγνωση/εγγραφή IFontFallBackRulesCollection. |

 **Επιστρέφει:**
[FontFallBackRulesCollection](../fontfallbackrulescollection)


---


### getFontSubstRuleList {#getFontSubstRuleList}

| Όνομα | Περιγραφή |
| --- | --- |
| getFontSubstRuleList () | Υποκατάστατα γραμματοσειρών για χρήση κατά την απόδοση. Ανάγνωση/εγγραφή IFontSubstRuleCollection. |

 **Επιστρέφει:**
[FontSubstRuleCollection](../fontsubstrulecollection)


---


### getFonts {#getFonts}

| Όνομα | Περιγραφή |
| --- | --- |
| getFonts () | Επιστρέφει τις γραμματοσειρές που χρησιμοποιούνται στην παρουσίαση |

 **Επιστρέφει:**
[FontData](../fontdata)


---


### getSubstitutions {#getSubstitutions}

| Όνομα | Περιγραφή |
| --- | --- |
| getSubstitutions () | Λαμβάνει τις πληροφορίες για τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση της παρουσίασης. |

 **Επιστρέφει:**
[CommentCollection](../commentcollection), [BehaviorPropertyCollection](../behaviorpropertycollection), [LineFormatCollection](../lineformatcollection), [ColumnCollection](../columncollection), SortedList, [ChartDataWorksheetCollection](../chartdataworksheetcollection), [SensitivityLabelCollection](../sensitivitylabelcollection), [EffectStyleCollection](../effectstylecollection), [GradientStopCollectionEffectiveData](../gradientstopcollectioneffectivedata), [SmartArtNodeCollection](../smartartnodecollection), [DigitalSignatureCollection](../digitalsignaturecollection), [TabCollection](../tabcollection), [PieSplitCustomPointCollection](../piesplitcustompointcollection), [SlideCollection](../slidecollection), List, [DrawingGuidesCollection](../drawingguidescollection), [ChartCategoryCollection](../chartcategorycollection), [SmartArtShapeCollection](../smartartshapecollection), [ShapeCollection](../shapecollection), [ImageTransformOperationCollection](../imagetransformoperationcollection), [FontFallBackRulesCollection](../fontfallbackrulescollection), SortedDictionary, [Sequence](../sequence), [RowCollection](../rowcollection), [SummaryZoomSectionCollection](../summaryzoomsectioncollection), LinkedList, [ChartSeriesCollection](../chartseriescollection), Stack, [ChartCellCollection](../chartcellcollection), [CommentAuthorCollection](../commentauthorcollection), Collection, [Row](../row), [AudioCollection](../audiocollection), [CustomXmlPartCollection](../customxmlpartcollection), [DataLabelCollection](../datalabelcollection), Dictionary, [MathBlock](../mathblock), [ImageTransformOCollectionEffectiveData](../imagetransformocollectioneffectivedata), [CaptionsCollection](../captionscollection), [TrendlineCollection](../trendlinecollection), [ParagraphCollection](../paragraphcollection), [MasterSlideCollection](../masterslidecollection), [TextAnimationCollection](../textanimationcollection), ReadOnlyCollection, [SectionCollection](../sectioncollection), [ChartDataPointCollection](../chartdatapointcollection), [MotionPath](../motionpath), [ControlPropertiesCollection](../controlpropertiescollection), [FontSubstRuleCollection](../fontsubstrulecollection), [BehaviorCollection](../behaviorcollection), [Column](../column), [VbaReferenceCollection](../vbareferencecollection), [PointCollection](../pointcollection), [ImageCollection](../imagecollection), [MasterLayoutSlideCollection](../masterlayoutslidecollection), [FillFormatCollection](../fillformatcollection), [GradientStopCollection](../gradientstopcollection), [PortionCollection](../portioncollection), [LayoutSlideCollection](../layoutslidecollection), Queue, [GlobalLayoutSlideCollection](../globallayoutslidecollection), [TagCollection](../tagcollection), [SequenceCollection](../sequencecollection), [ControlCollection](../controlcollection), [ExtraColorSchemeCollection](../extracolorschemecollection), [SectionSlideCollection](../sectionslidecollection), [ColorOperationCollection](../coloroperationcollection), [CellCollection](../cellcollection), [VbaModuleCollection](../vbamodulecollection), KeyedCollection, [MathParagraph](../mathparagraph), [VideoCollection](../videocollection)


---


### getSubstitutions {#getSubstitutions}

| Όνομα | Περιγραφή |
| --- | --- |
| getSubstitutions (int[]) | Λαμβάνει τις πληροφορίες για τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση των καθορισμένων διαφανειών. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| slides | int[] | Ένας πίνακας δεικτών διαφανειών για τους οποίους θα ανακτηθούν οι πληροφορίες υποκατάστασης γραμματοσειρών, ξεκινώντας από το 1. |

 **Επιστρέφει:**
[CommentCollection](../commentcollection), [BehaviorPropertyCollection](../behaviorpropertycollection), [LineFormatCollection](../lineformatcollection), [ColumnCollection](../columncollection), SortedList, [ChartDataWorksheetCollection](../chartdataworksheetcollection), [SensitivityLabelCollection](../sensitivitylabelcollection), [EffectStyleCollection](../effectstylecollection), [GradientStopCollectionEffectiveData](../gradientstopcollectioneffectivedata), [SmartArtNodeCollection](../smartartnodecollection), [DigitalSignatureCollection](../digitalsignaturecollection), [TabCollection](../tabcollection), [PieSplitCustomPointCollection](../piesplitcustompointcollection), [SlideCollection](../slidecollection), List, [DrawingGuidesCollection](../drawingguidescollection), [ChartCategoryCollection](../chartcategorycollection), [SmartArtShapeCollection](../smartartshapecollection), [ShapeCollection](../shapecollection), [ImageTransformOperationCollection](../imagetransformoperationcollection), [FontFallBackRulesCollection](../fontfallbackrulescollection), SortedDictionary, [Sequence](../sequence), [RowCollection](../rowcollection), [SummaryZoomSectionCollection](../summaryzoomsectioncollection), LinkedList, [ChartSeriesCollection](../chartseriescollection), Stack, [ChartCellCollection](../chartcellcollection), [CommentAuthorCollection](../commentauthorcollection), Collection, [Row](../row), [AudioCollection](../audiocollection), [CustomXmlPartCollection](../customxmlpartcollection), [DataLabelCollection](../datalabelcollection), Dictionary, [MathBlock](../mathblock), [ImageTransformOCollectionEffectiveData](../imagetransformocollectioneffectivedata), [CaptionsCollection](../captionscollection), [TrendlineCollection](../trendlinecollection), [ParagraphCollection](../paragraphcollection), [MasterSlideCollection](../masterslidecollection), [TextAnimationCollection](../textanimationcollection), ReadOnlyCollection, [SectionCollection](../sectioncollection), [ChartDataPointCollection](../chartdatapointcollection), [MotionPath](../motionpath), [ControlPropertiesCollection](../controlpropertiescollection), [FontSubstRuleCollection](../fontsubstrulecollection), [BehaviorCollection](../behaviorcollection), [Column](../column), [VbaReferenceCollection](../vbareferencecollection), [PointCollection](../pointcollection), [ImageCollection](../imagecollection), [MasterLayoutSlideCollection](../masterlayoutslidecollection), [FillFormatCollection](../fillformatcollection), [GradientStopCollection](../gradientstopcollection), [PortionCollection](../portioncollection), [LayoutSlideCollection](../layoutslidecollection), Queue, [GlobalLayoutSlideCollection](../globallayoutslidecollection), [TagCollection](../tagcollection), [SequenceCollection](../sequencecollection), [ControlCollection](../controlcollection), [ExtraColorSchemeCollection](../extracolorschemecollection), [SectionSlideCollection](../sectionslidecollection), [ColorOperationCollection](../coloroperationcollection), [CellCollection](../cellcollection), [VbaModuleCollection](../vbamodulecollection), KeyedCollection, [MathParagraph](../mathparagraph), [VideoCollection](../videocollection)


---


### removeEmbeddedFont {#removeEmbeddedFont}

| Όνομα | Περιγραφή |
| --- | --- |
| removeEmbeddedFont ([FontData](../fontdata)) | Αφαιρεί την ενσωματωμένη γραμματοσειρά |

 **Επιστρέφει:**
void


---


### replaceFont {#replaceFont}

| Όνομα | Περιγραφή |
| --- | --- |
| replaceFont ([FontData](../fontdata), [FontData](../fontdata)) | Αντικαθιστά τη γραμματοσειρά στην παρουσίαση |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceFont | [FontData](../fontdata) | Γραμματοσειρά πηγής |
| destFont | [FontData](../fontdata) | Γραμματοσειρά προορισμού |

 **Επιστρέφει:**
void


---


### replaceFont {#replaceFont}

| Όνομα | Περιγραφή |
| --- | --- |
| replaceFont ([FontSubstRule](../fontsubstrule)) | Αντικαθιστά τη γραμματοσειρά στην παρουσίαση χρησιμοποιώντας τις πληροφορίες που παρέχονται στο FontSubstRule |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| substRule | [FontSubstRule](../fontsubstrule) | Πληροφορίες υποκατάστασης γραμματοσειράς |

 **Επιστρέφει:**
void


---


### replaceFont {#replaceFont}

| Όνομα | Περιγραφή |
| --- | --- |
| replaceFont ([FontSubstRuleCollection](../fontsubstrulecollection)) | Αντικαθιστά τη γραμματοσειρά στην παρουσίαση χρησιμοποιώντας τη συλλογή κανόνων FontSubstRule |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| substRules | [FontSubstRuleCollection](../fontsubstrulecollection) | Συλλογή κανόνων υποκατάστασης γραμματοσειρών |

 **Επιστρέφει:**
void


---


### setFontFallBackRulesCollection {#setFontFallBackRulesCollection}

| Όνομα | Περιγραφή |
| --- | --- |
| setFontFallBackRulesCollection ([FontFallBackRulesCollection](../fontfallbackrulescollection)) | Αντιπροσωπεύει τη συλλογή κανόνων FontFallBack ενός χρήστη για τη διαχείριση συλλογών γραμματοσειρών για σωστές αντικαταστάσεις με τη λειτουργία fallback. Ανάγνωση/εγγραφή IFontFallBackRulesCollection. |

 **Επιστρέφει:**
void


---


### setFontSubstRuleList {#setFontSubstRuleList}

| Όνομα | Περιγραφή |
| --- | --- |
| setFontSubstRuleList ([FontSubstRuleCollection](../fontsubstrulecollection)) | Υποκατάστατα γραμματοσειρών για χρήση κατά την απόδοση. Ανάγνωση/εγγραφή IFontSubstRuleCollection. |

 **Επιστρέφει:**
void


---