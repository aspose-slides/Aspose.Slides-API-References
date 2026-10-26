---
title: EmbeddingLevel
second_title: Aspose.Slides Androidhoz Java API Referencia
description: A betűkészlet beágyazásához kapcsolódó licencjogokat képviseli.
type: docs
url: /hu/com.aspose.slides/embeddinglevel/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

A betűkészlet beágyazásához kapcsolódó licencjogokat képviseli.

## Mezők

| Field | Description |
| --- | --- |
| [Installable](#Installable) | Az ezzel a beállítással rendelkező betűkészletek jelzik, hogy egy alkalmazás beágyazhatja őket, és véglegesen telepítheti a távoli rendszeren. |
| [Restricted](#Restricted) | Azok a betűkészletek, amelyeknél csak ez a bit van beállítva, nem módosíthatók, beágyazhatók vagy cserélhetők semmilyen módon, amíg a jogtulajdonos engedélyét meg nem szerzik. |
| [PreviewPrint](#PreviewPrint) | Ha ez a bit be van állítva, a betűkészlet beágyazható, és ideiglenesen betölthető a távoli rendszeren. |
| [Editable](#Editable) | Ha ez a bit be van állítva, a betűkészlet beágyazható, de csak ideiglenesen telepíthető más rendszereken. |
| [NoSubsetting](#NoSubsetting) | Ha ez a bit be van állítva, a betűkészletet nem szabad részhalmazra csökkenteni a beágyazás előtt. |
| [BitmapOnly](#BitmapOnly) | Ha ez a bit be van állítva, csak a betűkészletben lévő bitkép (bitmap) ábrák ágyazhatók be. |

### Installable {#Installable}
```
public static final int Installable
```

Az ezzel a beállítással rendelkező betűkészletek jelzik, hogy egy alkalmazás beágyazhatja őket, és véglegesen telepítheti a távoli rendszeren. A távoli rendszer felhasználója ugyanazon jogokat, kötelezettségeket és licenceket kapja meg a betűkészletre vonatkozóan, mint a betűkészlet eredeti vásárlója, és ugyanazt a felhasználói licencszerződést, szerzői jogot, formatervezési szabadalmat és/vagy védjegyet vonja maga után, mint az eredeti vásárló.

### Restricted {#Restricted}
```
public static final int Restricted
```

Azok a betűkészletek, amelyeknél csak ez a bit van beállítva, nem módosíthatók, beágyazhatók vagy cserélhetők semmilyen módon, amíg a jogtulajdonos engedélyét meg nem szerzik.

### PreviewPrint {#PreviewPrint}
```
public static final int PreviewPrint
```

Ha ez a bit be van állítva, a betűkészlet beágyazható, és ideiglenesen betölthető a távoli rendszeren. A Preview & Print betűkészletet tartalmazó dokumentumokat csak "read-only" módban lehet megnyitni; a dokumentumon nem végezhető szerkesztés.

### Editable {#Editable}
```
public static final int Editable
```

Ha ez a bit be van állítva, a betűkészlet beágyazható, de csak ideiglenesen telepíthető más rendszereken. A Preview & Print betűkészletekkel ellentétben, az Editable betűkészletet tartalmazó dokumentumok megnyithatók olvasásra, a szerkesztés engedélyezett, és a módosítások menthetők.

### NoSubsetting {#NoSubsetting}
```
public static final int NoSubsetting
```

Ha ez a bit be van állítva, a betűkészletet nem szabad részhalmazra csökkenteni a beágyazás előtt. A 0-3 és 9 bites pozíciókban meghatározott egyéb beágyazási korlátozások is érvényesek.

### BitmapOnly {#BitmapOnly}
```
public static final int BitmapOnly
```

Ha ez a bit be van állítva, csak a betűkészletben található bitkép (bitmap) ábrák ágyazhatók be. Körvonaladatok beágyazása nem megengedett. Ha a betűkészletben nincs elérhető bitmap, akkor a betűkészletet beágyazhatatlannak tekintik, és a beágyazási szolgáltatás hibával lezárul.