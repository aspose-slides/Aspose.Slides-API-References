---
title: ISvgShape
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente les options pour une forme SVG.
type: docs
url: /fr/com.aspose.slides/isvgshape/
---```
public interface ISvgShape
```

Représente les options pour une forme SVG.
## Méthodes

| Méthode | Description |
| --- | --- |
| [setEventHandler(int eventType, String handler)](#setEventHandler-int-java.lang.String-) | Définit le gestionnaire d'événement pour la forme |
| [getId()](#getId--) | Définit ou récupère l'identifiant de la forme |
| [setId(String value)](#setId-java.lang.String-) | Définit ou récupère l'identifiant de la forme |
### setEventHandler(int eventType, String handler) {#setEventHandler-int-java.lang.String-}
```
public abstract void setEventHandler(int eventType, String handler)
```

Définit le gestionnaire d'événement pour la forme

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| eventType | int | Type d'événement. |
| handler | java.lang.String | Fonction Javascript pour gérer l'événement. Une valeur nulle supprime le gestionnaire. |

### getId() {#getId--}
```
public abstract String getId()
```

Définit ou récupère l'identifiant de la forme

**Renvoie :**
java.lang.String

### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

Définit ou récupère l'identifiant de la forme

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |