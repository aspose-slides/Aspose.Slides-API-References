---
title: ChartPortionFormat
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Cette classe contient les propriétés de formatage des parties de graphique utilisées dans les graphiques.
type: docs
url: /fr/com.aspose.slides/chartportionformat/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
```
public final class ChartPortionFormat extends BasePortionFormat implements IChartPortionFormat
```

Cette classe contient les propriétés de formatage des parties de graphique utilisées dans les graphiques. Contrairement à [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), toutes les propriétés de cette classe sont modifiables.

--------------------

Cette classe est utilisée pour renvoyer et manipuler les propriétés de formatage des parties de texte définies pour la partie particulière. Cela signifie qu'aucune héritage n'est appliquée lors de la récupération des valeurs, de sorte que dans la plupart des cas vous obtiendrez des valeurs signifiant « indéfini ».

Afin d'obtenir les valeurs effectives des paramètres de formatage, y compris celles héritées, vous devez utiliser la méthode [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) qui renvoie une instance [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Renvoie :**
long