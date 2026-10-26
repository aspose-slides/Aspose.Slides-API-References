---
title: ParagraphCollection
second_title: Aspose.Sildes pour PHP via la référence de l'API Java
description: 
type: docs

url: /fr/aspose.slides/paragraphcollection/
---
## ParagraphCollection classe

 Représente une collection de paragraphes.

### add {#add}

| Nom | Description |
| --- | --- |
| add ([Paragraph](../paragraph)) | Ajoute un Paragraph à la fin de la collection. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| value | [Paragraph](../paragraph) | Le Paragraph à ajouter à la fin de la collection. |

**Renvoie:**
void

---

### add {#add}

| Nom | Description |
| --- | --- |
| add ([ParagraphCollection](../paragraphcollection)) | Ajoute le contenu de ParagraphCollection à la fin de la collection. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| value | [ParagraphCollection](../paragraphcollection) | Le ParagraphCollection à ajouter à la fin de la collection. |

**Renvoie:**
int

---

### addFromHtml {#addFromHtml}

| Nom | Description |
| --- | --- |
| addFromHtml (String) | Ajoute du texte à partir de la chaîne html spécifiée à la collection. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| text | String | Texte HTML. |

**Renvoie:**
void

---

### addFromHtml {#addFromHtml}

| Nom | Description |
| --- | --- |
| addFromHtml (String, [HtmlExternalResolver](../htmlexternalresolver), String) | Ajoute du texte à partir de la chaîne html spécifiée à la collection. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| text | String | Texte HTML. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | Objet de rappel Resolver qui résout les URI et récupère les objets référencés. |
| uri | String | URI pour ajouter le document HTML. Utilisé pour résoudre les liens relatifs. Spécifier le résolveur peut potentiellement introduire une vulnérabilité. À utiliser avec prudence. |

**Renvoie:**
void

---

### addFromHtml {#addFromHtml}

| Nom | Description |
| --- | --- |
| addFromHtml (String, [ExternalResourceResolver](../externalresourceresolver), String) | Ajoute du texte à partir de la chaîne html spécifiée à la collection. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| text | String | Texte HTML. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | Objet de rappel Resolver qui résout les URI et récupère les objets référencés. |
| uri | String | URI pour ajouter le document HTML. Utilisé pour résoudre les liens relatifs. Spécifier le résolveur peut potentiellement introduire une vulnérabilité. À utiliser avec prudence. |

**Renvoie:**
void

---

### clear {#clear}

| Nom | Description |
| --- | --- |
| clear () | Supprime tous les éléments de la collection. |

**Renvoie:**
void

---

### contains {#contains}

| Nom | Description |
| --- | --- |
| contains ([Paragraph](../paragraph)) | Détermine si IGenericCollection contient une valeur spécifique. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| item | [Paragraph](../paragraph) | L'objet à localiser dans IGenericCollection. |

**Renvoie:**
boolean

---

### copyTo {#copyTo}

| Nom | Description |
| --- | --- |
| copyTo (com.aspose.slides.IParagraph[], int) | Copie les éléments de IGenericCollection dans un Array, en commençant à un index de tableau particulier. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| array | com.aspose.slides.IParagraph[] | Le Array unidimensionnel qui est la destination des éléments copiés depuis IGenericCollection. L'Array doit avoir une indexation à base zéro. |
| arrayIndex | int | L'index basé sur zéro dans le tableau où la copie commence. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Le nombre d'éléments dans le IGenericCollection source est supérieur à l'espace disponible depuis arrayIndex jusqu'à la fin du tableau de destination. |

---

### exportToHtml {#exportToHtml}

| Nom | Description |
| --- | --- |
| exportToHtml (int, int, [TextToHtmlConversionOptions](../texttohtmlconversionoptions)) | Convertit les paragraphes spécifiés en HTML et renvoie le résultat comme objet String. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| firstParagraphIndex | int | Index du premier paragraphe int |
| paragraphsCount | int | Nombre de paragraphes int |
| options | [TextToHtmlConversionOptions](../texttohtmlconversionoptions) | Options de conversion ITextToHtmlConversionOptions |

**Renvoie:**
String

---

### getCount {#getCount}

| Nom | Description |
| --- | --- |
| getCount () | Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule int. |

**Renvoie:**
int

---

### getPresentation {#getPresentation}

| Nom | Description |
| --- | --- |
| getPresentation () | Renvoie la présentation parent d'une collection de paragraphes. Lecture seule IPresentation. |

**Renvoie:**
[Presentation](../presentation)

---

### getSlide {#getSlide}

| Nom | Description |
| --- | --- |
| getSlide () | Renvoie la diapositive parent d'une collection de paragraphes. Lecture seule BaseSlide. |

**Renvoie:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)

---

### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Obtient l'élément à l'index spécifié. |

**Renvoie:**
[Paragraph](../paragraph)

---

### indexOf {#indexOf}

| Nom | Description |
| --- | --- |
| indexOf ([Paragraph](../paragraph)) | Détermine l'index d'un élément spécifique dans la List. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| item | [Paragraph](../paragraph) | L'objet à localiser dans la List. |

**Renvoie:**
int

---

### insert {#insert}

| Nom | Description |
| --- | --- |
| insert (int, [Paragraph](../paragraph)) | Insère un Paragraph dans la collection à l'index spécifié. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où le Paragraph doit être inséré. |
| value | [Paragraph](../paragraph) | Le Paragraph à insérer. |

**Renvoie:**
void

---

### insert {#insert}

| Nom | Description |
| --- | --- |
| insert (int, [ParagraphCollection](../paragraphcollection)) | Insère le contenu de ParagraphCollection dans la collection à l'index spécifié. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où les paragraphes doivent être insérés. |
| value | [ParagraphCollection](../paragraphcollection) | Les paragraphes à insérer. |

**Renvoie:**
void

---

### isReadOnly {#isReadOnly}

| Nom | Description |
| --- | --- |
| isReadOnly () | Obtient une valeur indiquant si IGenericCollection est en lecture seule. Lecture seule boolean. |

**Renvoie:**
boolean

---

### iterator {#iterator}

| Nom | Description |
| --- | --- |
| iterator () | Renvoie un énumérateur qui parcourt la collection. |

**Renvoie:**



---

### iteratorJava {#iteratorJava}

| Nom | Description |
| --- | --- |
| iteratorJava () | Renvoie un itérateur Java pour la collection entière. |

**Renvoie:**



---

### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([Paragraph](../paragraph)) | Supprime la première occurrence d'un objet spécifique de IGenericCollection. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| item | [Paragraph](../paragraph) | L'objet à supprimer de IGenericCollection. |

**Renvoie:**
boolean

**Exception**

| Erreur | Condition |
| --- | --- |
| NotSupportedException | Le IGenericCollection est en lecture seule. |

---

### removeAt {#removeAt}

| Nom | Description |
| --- | --- |
| removeAt (int) | Supprime l'élément à l'index spécifié de la collection. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à supprimer. |

**Renvoie:**
void

---