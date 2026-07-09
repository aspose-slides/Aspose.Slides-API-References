---
title: ISectionCollection
second_title: Référence de l'API Aspose.Slides pour Android via Java
description: Représente une collection de sections.
type: docs
url: /fr/com.aspose.slides/isectioncollection/
---
**Toutes les interfaces implémentées :**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

Représente une collection de sections.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Ajoute une nouvelle section démarrée à partir d'une diapositive spécifique. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Ajoute une section vide à la position spécifiée de la collection. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Supprime la section et les diapositives contenues dans la section. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Supprime la section. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Déplace la section et ses diapositives de la collection vers la position spécifiée. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Ajoute une section vide à la fin de la collection. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Renvoie l'index de la section spécifiée dans la collection. |
| [clear()](#clear--) | Supprime toutes les sections de la collection. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```

Obtient l'élément à l'index spécifié. Read-only [ISection](../../com.aspose.slides/isection).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour :**
[ISection](../../com.aspose.slides/isection)

### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```

Ajoute une nouvelle section démarrée à partir d'une diapositive spécifique.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la section |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Première diapositive de la section |

**Retour :**
[ISection](../../com.aspose.slides/isection) - Section ajoutée.

### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

Ajoute une section vide à la position spécifiée de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la section |
| index | int | Index de la nouvelle section. |

**Retour :**
[ISection](../../com.aspose.slides/isection) - Section ajoutée.

### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

Supprime la section et les diapositives contenues dans la section.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | La section à supprimer de la collection. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

Supprime la section. Les diapositives contenues dans la section seront fusionnées avec la section précédente.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | La section à supprimer de la collection. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

Déplace la section et ses diapositives de la collection vers la position spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Section à déplacer. |
| index | int | Index cible. |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

Ajoute une section vide à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la section |

**Retour :**
[ISection](../../com.aspose.slides/isection) - Section ajoutée.

### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

Renvoie l'index de la section spécifiée dans la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Section à rechercher. |

**Retour :**
int - Index d'une section ou -1 si la section ne provient pas de cette collection.

### clear() {#clear--}
```
public abstract void clear()
```

Supprime toutes les sections de la collection.