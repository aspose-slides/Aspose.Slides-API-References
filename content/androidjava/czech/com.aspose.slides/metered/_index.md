---
title: Metered
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Poskytuje metody pro nastavení měřeného klíče.
type: docs
url: /cs/com.aspose.slides/metered/
---
**Dědičnost:**
java.lang.Object
```
public class Metered
```

Poskytuje metody pro nastavení měřeného klíče.
## Konstruktory

| Constructor | Description |
| --- | --- |
| [Metered()](#Metered--) | Inicializuje novou instanci této třídy. |
## Metody

| Method | Description |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Nastavuje měřený veřejný a soukromý klíč. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Získá velikost souboru spotřeby |
| [getConsumptionCredit()](#getConsumptionCredit--) | Získá kredit spotřeby |
| [isMeteredLicensed()](#isMeteredLicensed--) | Zkontroluje, zda je měřený licencován |
### Metered() {#Metered--}
```
public Metered()
```

Inicializuje novou instanci této třídy.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

Nastavuje měřený veřejný a soukromý klíč. Pokud zakoupíte měřenou licenci, při spuštění aplikace by se toto API mělo zavolat; obvykle to stačí. Avšak pokud se opakovaně nedaří nahrát data o spotřebě a uplyne 24 hodin, licence bude přepnuta do stavu vyhodnocení. Aby se taková situace předešla, měli byste pravidelně kontrolovat stav licence; pokud je ve stavu vyhodnocení, zavolejte toto API znovu.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String | veřejný klíč |
| privateKey | java.lang.String | soukromý klíč |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```

Získá velikost souboru spotřeby

**Návratová hodnota:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```

Získá kredit spotřeby

**Návratová hodnota:**
double - spotřební množství
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```

Zkontroluje, zda je měřený licencován

**Návratová hodnota:**
boolean - True nebo false