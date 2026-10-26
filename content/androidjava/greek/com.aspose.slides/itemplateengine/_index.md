---
title: ITemplateEngine
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a template engine that transforms template and data pair into resulting output usually HTML.
type: docs
url: /el/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Αναπαριστά μια μηχανή προτύπων που μετατρέπει το ζεύγος προτύπου και δεδομένων σε τελικό αποτέλεσμα (συνήθως HTML).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Προσθέτει το πρότυπο στη συλλογή προτύπων. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Μετατρέπει το πρότυπο με το δεδομένο κλειδί και το αντικείμενο μοντέλου σε έξοδο. |
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
| modelType | com.aspose.ms.System.Type | Τύπος αντικειμένου μοντέλου για το πρότυπο. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

Μετατρέπει το πρότυπο με το δεδομένο κλειδί και το αντικείμενο μοντέλου σε έξοδο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| key | java.lang.String | Κλειδί για το πρότυπο στη συλλογή προτύπων. |
| model | java.lang.Object | Αντικείμενο μοντέλου με δεδομένα για τη μετασχηματισμό. |

**Επιστρέφει:**
java.lang.String - Παραγόμενο αποτέλεσμα ως String.