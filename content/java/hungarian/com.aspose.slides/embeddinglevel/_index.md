---
title: EmbeddingLevel
second_title: Aspose.Slides Java API Referencia
description: A betűtípus beágyazásához kapcsolódó licencjogokat jelenti.
type: docs
url: /hu/com.aspose.slides/embeddinglevel/
---
**Öröklés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

A betűtípus beágyazásához kapcsolódó licencjogokat jelenti.
## Mezők

| Mező | Leírás |
| --- | --- |
| [Installable](#Installable) | Az ebben a beállításban szereplő betűtípusok jelzik, hogy beágyazhatók, és az alkalmazás által a távoli rendszeren végleges telepítésre kerülhetnek. |
| [Restricted](#Restricted) | Azok a betűtípusok, amelyeknél csak ez a bit van beállítva, semmilyen módon nem módosíthatók, beágyazhatók vagy cserélhetők, amíg a jogtulajdonos engedélye nem áll rendelkezésre. |
| [PreviewPrint](#PreviewPrint) | Ha ez a bit be van állítva, a betűtípus beágyazható, és ideiglenesen betölthető a távoli rendszerre. |
| [Editable](#Editable) | Ha ez a bit be van állítva, a betűtípus beágyazható, de csak ideiglenesen telepíthető más rendszerekre. |
| [NoSubsetting](#NoSubsetting) | Ha ez a bit be van állítva, a betűtípus beágyazása előtt nem szabad részhalmazra bontani. |
| [BitmapOnly](#BitmapOnly) | Ha ez a bit be van állítva, csak a betűtípusban szereplő bitképek ágyazhatók be. |
### Installable {#Installable}
```
public static final int Installable
```

Az ebben a beállításban szereplő betűtípusok jelzik, hogy beágyazhatók, és az alkalmazás által a távoli rendszeren végleges telepítésre kerülhetnek. A távoli rendszer felhasználója ugyanolyan jogokkal, kötelezettségekkel és licencekkel rendelkezik az adott betűtípusra, mint a betűtípust eredetileg megvásárló személy, és ugyanazt a végfelhasználói licencszerződést, szerzői jogot, tervezési szabadalmat és/vagy védjegyet kell betartania, mint az eredeti vásárló.

### Restricted {#Restricted}
```
public static final int Restricted
```

Azok a betűtípusok, amelyeknél csak ez a bit van beállítva, semmilyen módon nem módosíthatók, beágyazhatók vagy cserélhetők, amíg a jogtulajdonos engedélye nem áll rendelkezésre.

### PreviewPrint {#PreviewPrint}
```
public static final int PreviewPrint
```

Ha ez a bit be van állítva, a betűtípus beágyazható, és ideiglenesen betölthető a távoli rendszerre. A Preview & Print betűtípusokat tartalmazó dokumentumokat csak „read-only” módban lehet megnyitni; a dokumentumot nem lehet szerkeszteni.

### Editable {#Editable}
```
public static final int Editable
```

Ha ez a bit be van állítva, a betűtípus beágyazható, de csak ideiglenesen telepíthető más rendszerekre. A Preview & Print betűtípusokkal szemben az Editable betűtípusokat tartalmazó dokumentumok olvasásra megnyithatók, a szerkesztés megengedett, és a módosítások menthetők.

### NoSubsetting {#NoSubsetting}
```
public static final int NoSubsetting
```

Ha ez a bit be van állítva, a betűtípus beágyazása előtt nem lehet részhalmazra bontani. A 0-3 és 9. bitekben meghatározott egyéb beágyazási korlátozások szintén érvényesek.

### BitmapOnly {#BitmapOnly}
```
public static final int BitmapOnly
```

Ha ez a bit be van állítva, csak a betűtípusban található bitképek ágyazhatók be. Kontúradatok nem ágyazhatók be. Ha a betűtípusban nincs elérhető bitkép, akkor a betűtípus beágyazhatatlannak tekintendő, és a beágyazási szolgáltatás hibára fut.