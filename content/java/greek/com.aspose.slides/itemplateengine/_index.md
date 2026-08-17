---
title: ITemplateEngine
second_title: Aspose.Slides for Java API Reference
description: Αναπαριστά μια μηχανή προτύπου που μετατρέπει το ζεύγος προτύπου και δεδομένων σε αποτέλεσμα εξόδου, συνήθως HTML.
type: docs
url: /el/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Αναπαριστά μια μηχανή προτύπου που μετατρέπει το ζεύγος προτύπου και δεδομένων σε αποτέλεσμα εξόδου (συνήθως HTML).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Προσθέτει το πρότυπο στη συλλογή προτύπων. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Μετασχηματίζει το πρότυπο με το δοθέν κλειδί και το αντικείμενο μοντέλου στην έξοδο. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

Προσθέτει το πρότυπο στη συλλογή προτύπων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| key | java.lang.String | Κλειδί για το πρότυπο στη συλλογή προτύπων. |
| template | java.lang.String | Περιεχόμενο προτύπου. |
| modelType | com.aspose.ms.System.Type | Τύπος ενός αντικειμένου μοντέλου για το πρότυπο. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

Μετασχηματίζει το πρότυπο με το δοθέν κλειδί και το αντικείμενο μοντέλου στην έξοδο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| key | java.lang.String | Κλειδί για το πρότυπο στη συλλογή προτύπων. |
| model | java.lang.Object | Αντικείμενο μοντέλου με δεδομένα για τη μετασχηματισμό. |

**Επιστρέφει:**
java.lang.String - Το αποτέλεσμα εξόδου ως String.