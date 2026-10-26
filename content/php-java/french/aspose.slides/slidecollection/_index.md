---
title: SlideCollection
second_title: Aspose.Sildes pour PHP via la référence d'API Java
description: 
type: docs

url: /fr/aspose.slides/slidecollection/
---
## SlideCollection classe

 Représente une collection de Slides.
 
### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([Slide](../slide)) | Ajoute une copie d’une Slide spécifiée à la fin de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | Slide à dupliquer. Lors du clonage d’une Slide entre différentes présentations, le master de la Slide peut également être cloné. Un registre interne est utilisé pour suivre les masters clonés automatiquement afin d’éviter la création de plusieurs clones du même master Slide. Le clonage manuel des masters Slides ne sera ni empêché ni enregistré. Si vous avez besoin de plus de contrôle sur le processus de clonage, utilisez #addClone(ISlide,ILayoutSlide) ou #addClone(ISlide,IMasterSlide,boolean) pour cloner les Slides, IGlobalLayoutSlideCollection#addClone(ILayoutSlide) ou IGlobalLayoutSlideCollection#addClone(ILayoutSlide,IMasterSlide) pour cloner les layouts et IMasterSlideCollection#addClone(IMasterSlide) pour cloner les masters. |

 **Retour :**
[Slide](../slide)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([Slide](../slide), [Section](../section)) | Ajoute une copie d’une Slide spécifiée à la fin de la section spécifiée. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | Slide à dupliquer. |
| section | [Section](../section) | Section pour la nouvelle Slide. |

 **Retour :**
[Slide](../slide)

 **Exception**

| Erreur | Condition |
| --- | --- |
 | PptxEditException | Lorsque le paramètre section contient une valeur incorrecte ou invalide. |

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([Slide](../slide), [LayoutSlide](../layoutslide)) | Ajoute une copie d’une Slide spécifiée à la fin de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | Slide à dupliquer. |
| destLayout | [LayoutSlide](../layoutslide) | Layout Slide pour la nouvelle Slide. |

 **Retour :**
[Slide](../slide)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([Slide](../slide), [MasterSlide](../masterslide), boolean) | Ajoute une copie d’une Slide source spécifiée à la fin de la collection. Le layout approprié sera sélectionné automatiquement à partir du master spécifié (le layout approprié est celui ayant le même Type ou le même Name que le layout de la Slide source). S’il n’y a aucun layout approprié, le layout de la Slide source sera cloné (si allowCloneMissingLayout est vrai) ou une PptxEditException sera levée (si allowCloneMissingLayout est faux). |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | Slide à dupliquer. |
| destMaster | [MasterSlide](../masterslide) | Master Slide pour la nouvelle Slide. |
| allowCloneMissingLayout | boolean | Si aucun layout approprié n’existe dans le master spécifié, le layout de la Slide source sera cloné (si allowCloneMissingLayout est vrai) ou une PptxEditException sera levée (si allowCloneMissingLayout est faux). |

 **Retour :**
[Slide](../slide)

 **Exception**

| Erreur | Condition |
| --- | --- |
 | PptxEditException | Levée s’il n’y a aucun layout approprié dans le master spécifié et que allowCloneMissingLayout est faux. |

---

### addEmptySlide {#addEmptySlide}

| Nom | Description |
| --- | --- |
| addEmptySlide ([LayoutSlide](../layoutslide)) | Ajoute une nouvelle Slide vide à la fin de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| layout | [LayoutSlide](../layoutslide) | Layout pour une Slide. |

 **Retour :**
[Slide](../slide)

---

### addFromHtml {#addFromHtml}

| Nom | Description |
| --- | --- |
| addFromHtml (String, [HtmlExternalResolver](../htmlexternalresolver), String) | Crée des Slides à partir de texte HTML et les ajoute à la fin de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| htmlText | String | Html à ajouter. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | Objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est nul, tous les objets externes seront ignorés. |
| uri | String | URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |

 **Retour :**
[Slide](../slide)

---

### addFromHtml {#addFromHtml}

| Nom | Description |
| --- | --- |
| addFromHtml (String, [ExternalResourceResolver](../externalresourceresolver), String) | Crée des Slides à partir de texte HTML et les ajoute à la fin de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| htmlText | String | Html à ajouter. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | Objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est nul, tous les objets externes seront ignorés. |
| uri | String | URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |

 **Retour :**
[Slide](../slide)

---

### addFromHtml {#addFromHtml}

| Nom | Description |
| --- | --- |
| addFromHtml (String) | Crée des Slides à partir de texte HTML et les ajoute à la fin de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| htmlText | String | Html à ajouter. |

 **Retour :**
[Slide](../slide)

---

### addFromHtml {#addFromHtml}

| Nom | Description |
| --- | --- |
| addFromHtml (InputStream, [HtmlExternalResolver](../htmlexternalresolver), String) | Crée des Slides à partir de texte HTML et les ajoute à la fin de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| htmlStream | InputStream | Objet Stream utilisé comme source du fichier HTML. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | Objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est nul, tous les objets externes seront ignorés. |
| uri | String | URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |

 **Retour :**
[Slide](../slide)

---

### addFromHtml {#addFromHtml}

| Nom | Description |
| --- | --- |
| addFromHtml (InputStream, [ExternalResourceResolver](../externalresourceresolver), String) | Crée des Slides à partir de texte HTML et les ajoute à la fin de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| htmlStream | InputStream | Objet Stream utilisé comme source du fichier HTML. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | Objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est nul, tous les objets externes seront ignorés. |
| uri | String | URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |

 **Retour :**
[Slide](../slide)

---

### addFromHtml {#addFromHtml}

| Nom | Description |
| --- | --- |
| addFromHtml (InputStream) | Crée des Slides à partir de texte HTML et les ajoute à la fin de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| htmlStream | InputStream | Objet Stream utilisé comme source du fichier HTML. |

 **Retour :**
[Slide](../slide)

---

### addFromPdf {#addFromPdf}

| Nom | Description |
| --- | --- |
| addFromPdf (String) | Crée des Slides à partir du document PDF et les ajoute à la fin de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| path | String | Chemin vers le document PDF |

 **Retour :**
[Slide](../slide)

---

### addFromPdf {#addFromPdf}

| Nom | Description |
| --- | --- |
| addFromPdf (String, [PdfImportOptions](../pdfimportoptions)) | Crée des Slides à partir du document PDF et les ajoute à la fin de la collection en tenant compte des options d’import PDF. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| path | String | Chemin vers le document PDF |
| pdfImportOptions | [PdfImportOptions](../pdfimportoptions) | Options d’import PDF |

 **Retour :**
[Slide](../slide)

---

### addFromPdf {#addFromPdf}

| Nom | Description |
| --- | --- |
| addFromPdf (InputStream) | Crée des Slides à partir du document PDF et les ajoute à la fin de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pdfStream | InputStream | Stream utilisé comme source du document PDF |

 **Retour :**
[Slide](../slide)

---

### addFromPdf {#addFromPdf}

| Nom | Description |
| --- | --- |
| addFromPdf (InputStream, [PdfImportOptions](../pdfimportoptions)) | Crée des Slides à partir du document PDF et les ajoute à la fin de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pdfStream | InputStream | Stream utilisé comme source du document PDF |
| pdfImportOptions | [PdfImportOptions](../pdfimportoptions) | Options d’import PDF |

 **Retour :**
[Slide](../slide)

---

### getSyncRoot {#getSyncRoot}

| Nom | Description |
| --- | --- |
| getSyncRoot () | Retourne une racine de synchronisation. En lecture seule Object. |

 **Retour :**
Object

---

### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Obtient l’élément à l’index spécifié. En lecture seule Slide. |

 **Retour :**
[Slide](../slide)

---

### indexOf {#indexOf}

| Nom | Description |
| --- | --- |
| indexOf ([Slide](../slide)) | Retourne l’index de la Slide spécifiée dans la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| slide | [Slide](../slide) | Slide à trouver. |

 **Retour :**
int

---

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [Slide](../slide)) | Insère une copie d’une Slide spécifiée à la position indiquée de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Index de la nouvelle Slide. |
| sourceSlide | [Slide](../slide) | Slide à dupliquer. Lors du clonage d’une Slide entre différentes présentations, le master de la Slide peut également être cloné. Un registre interne est utilisé pour suivre les masters clonés automatiquement afin d’éviter la création de plusieurs clones du même master Slide. Le clonage manuel des masters Slides ne sera ni empêché ni enregistré. Si vous avez besoin de plus de contrôle sur le processus de clonage, utilisez #insertClone(int,ISlide,ILayoutSlide) ou #insertClone(int,ISlide,IMasterSlide,boolean) pour cloner les Slides et IMasterSlideCollection#addClone(IMasterSlide) pour cloner les masters. |

 **Retour :**
[Slide](../slide)

---

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [Slide](../slide), [LayoutSlide](../layoutslide)) | Insère une copie d’une Slide spécifiée à la position indiquée de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Index de la nouvelle Slide. |
| sourceSlide | [Slide](../slide) | Slide à dupliquer. |
| destLayout | [LayoutSlide](../layoutslide) | Layout Slide pour une nouvelle Slide. |

 **Retour :**
[Slide](../slide)

---

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [Slide](../slide), [MasterSlide](../masterslide), boolean) | Insère une copie d’une Slide source spécifiée à la position indiquée de la collection. Le layout approprié sera sélectionné automatiquement à partir du master spécifié (le layout approprié est celui ayant le même Type ou le même Name que le layout de la Slide source). S’il n’y a aucun layout approprié, le layout de la Slide source sera cloné (si allowCloneMissingLayout est vrai) ou une PptxEditException sera levée (si allowCloneMissingLayout est faux). |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Index de la nouvelle Slide. |
| sourceSlide | [Slide](../slide) | Slide à dupliquer. |
| destMaster | [MasterSlide](../masterslide) | Master Slide pour une nouvelle Slide. |
| allowCloneMissingLayout | boolean | Si aucun layout approprié n’existe dans le master spécifié, le layout de la Slide source sera cloné (si allowCloneMissingLayout est vrai) ou une PptxEditException sera levée (si allowCloneMissingLayout est faux). |

 **Retour :**
[Slide](../slide)

 **Exception**

| Erreur | Condition |
| --- | --- |
 | PptxEditException | Levée s’il n’y a aucun layout approprié dans le master spécifié et que allowCloneMissingLayout est faux. |

---

### insertEmptySlide {#insertEmptySlide}

| Nom | Description |
| --- | --- |
| insertEmptySlide (int, [LayoutSlide](../layoutslide)) | Insère une copie d’une Slide spécifiée à la position indiquée de la collection. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Index d’une nouvelle Slide. |
| layout | [LayoutSlide](../layoutslide) | Layout pour une Slide. |

 **Retour :**
[Slide](../slide)

---

### insertFromHtml {#insertFromHtml}

| Nom | Description |
| --- | --- |
| insertFromHtml (int, String, [HtmlExternalResolver](../htmlexternalresolver), String) | Crée des Slides à partir de texte HTML et les insère dans la collection à la position spécifiée. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Position d’insertion. |
| htmlText | String | Html à ajouter. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | String | Un URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |

**Retour :**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Nom | Description |
| --- | --- |
| insertFromHtml (int, String, [ExternalResourceResolver](../externalresourceresolver), String) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Position où insérer. |
| htmlText | String | Html à ajouter. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | String | Un URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |

**Retour :**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Nom | Description |
| --- | --- |
| insertFromHtml (int, String, [HtmlExternalResolver](../htmlexternalresolver), String, boolean) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Position où insérer. |
| htmlText | String | Html à ajouter. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | String | Un URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |
| useSlideWithIndexAsStart | boolean | Ce drapeau détermine comment démarrer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index spécifié. Si vrai, l'insertion des données commencera à partir d'un espace vide sur la diapositive avec l'index spécifié. Si faux, les données seront ajoutées aux diapositives créées. |

**Retour :**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Nom | Description |
| --- | --- |
| insertFromHtml (int, String, [ExternalResourceResolver](../externalresourceresolver), String, boolean) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Position où insérer. |
| htmlText | String | Html à ajouter. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | String | Un URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |
| useSlideWithIndexAsStart | boolean | Ce drapeau détermine comment démarrer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index spécifié. Si vrai, l'insertion des données commencera à partir d'un espace vide sur la diapositive avec l'index spécifié. Si faux, les données seront ajoutées aux diapositives créées. |

**Retour :**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Nom | Description |
| --- | --- |
| insertFromHtml (int, String) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Position où insérer. |
| htmlText | String | Html à ajouter. |

**Retour :**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Nom | Description |
| --- | --- |
| insertFromHtml (int, String, boolean) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Position où insérer. |
| htmlText | String | Html à ajouter. |
| useSlideWithIndexAsStart | boolean | Ce drapeau détermine comment démarrer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index spécifié. Si vrai, l'insertion des données commencera à partir d'un espace vide sur la diapositive avec l'index spécifié. Si faux, les données seront ajoutées aux diapositives créées. |

**Retour :**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Nom | Description |
| --- | --- |
| insertFromHtml (int, InputStream, [HtmlExternalResolver](../htmlexternalresolver), String) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Position où insérer. |
| htmlStream | InputStream | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | String | Un URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |

**Retour :**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Nom | Description |
| --- | --- |
| insertFromHtml (int, InputStream, [ExternalResourceResolver](../externalresourceresolver), String) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Position où insérer. |
| htmlStream | InputStream | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | String | Un URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |

**Retour :**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Nom | Description |
| --- | --- |
| insertFromHtml (int, InputStream, [HtmlExternalResolver](../htmlexternalresolver), String, boolean) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Position où insérer. |
| htmlStream | InputStream | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | String | Un URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |
| useSlideWithIndexAsStart | boolean | Ce drapeau détermine comment démarrer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index spécifié. Si vrai, l'insertion des données commencera à partir d'un espace vide sur la diapositive avec l'index spécifié. Si faux, les données seront ajoutées aux diapositives créées. |

**Retour :**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Nom | Description |
| --- | --- |
| insertFromHtml (int, InputStream, [ExternalResourceResolver](../externalresourceresolver), String, boolean) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Position où insérer. |
| htmlStream | InputStream | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | String | Un URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |
| useSlideWithIndexAsStart | boolean | Ce drapeau détermine comment démarrer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index spécifié. Si vrai, l'insertion des données commencera à partir d'un espace vide sur la diapositive avec l'index spécifié. Si faux, les données seront ajoutées aux diapositives créées. |

**Retour :**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Nom | Description |
| --- | --- |
| insertFromHtml (int, InputStream) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Position où insérer. |
| htmlStream | InputStream | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |

**Retour :**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Nom | Description |
| --- | --- |
| insertFromHtml (int, InputStream, boolean) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Position où insérer. |
| htmlStream | InputStream | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| useSlideWithIndexAsStart | boolean | Ce drapeau détermine comment démarrer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index spécifié. Si vrai, l'insertion des données commencera à partir d'un espace vide sur la diapositive avec l'index spécifié. Si faux, les données seront ajoutées aux diapositives créées. |

**Retour :**
[Slide](../slide)


---


### isSynchronized {#isSynchronized}

| Nom | Description |
| --- | --- |
| isSynchronized () | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule booléen. |

**Retour :**
boolean


---


### iterator {#iterator}

| Nom | Description |
| --- | --- |
| iterator () | Renvoie un énumérateur qui parcourt la collection. |

**Retour :**



---


### iteratorJava {#iteratorJava}

| Nom | Description |
| --- | --- |
| iteratorJava () | Renvoie un itérateur java pour l'ensemble de la collection. |

**Retour :**



---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([Slide](../slide)) | Supprime la première occurrence d'un objet spécifique de la collection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| value | [Slide](../slide) | La diapositive à supprimer de la collection. |

**Retour :**
void


---


### removeAt {#removeAt}

| Nom | Description |
| --- | --- |
| removeAt (int) | Supprime l'élément à l'index spécifié de la collection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à supprimer. |

**Retour :**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentOutOfRangeException | Lorsque le paramètre index contient un numéro de section incorrect. |


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [Slide](../slide)) | Déplace la diapositive de la collection vers la position spécifiée. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Index cible. |
| slide | [Slide](../slide) | Diapositive à déplacer. |

**Retour :**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, com.aspose.slides.ISlide[]) | Déplace les diapositives de la collection vers la position spécifiée. Les diapositives seront placées à partir de l'index dans l'ordre où elles apparaissent dans la liste. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Index cible. |
| slides | com.aspose.slides.ISlide[] | Diapositives à déplacer. |

**Retour :**
void


---


### size {#size}

| Nom | Description |
| --- | --- |
| size () | Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule int. |

**Retour :**
int


---


### toArray {#toArray}

| Nom | Description |
| --- | --- |
| toArray () | Crée et renvoie un tableau contenant toutes les diapositives. |

**Retour :**
[Slide](../slide)


---


### toArray {#toArray}

| Nom | Description |
| --- | --- |
| toArray (int, int) | Crée et renvoie un tableau contenant toutes les diapositives de la plage spécifiée. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| startIndex | int | Un index de la première diapositive à ajouter. |
| count | int | Un nombre de diapositives à ajouter. |

**Retour :**
[Slide](../slide)