---
title: Metered
second_title: Aspose.Slides pro Java – reference API
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

| Konstruktor | Popis |
| --- | --- |
| [Metered()](#Metered--) | Inicializuje novou instanci této třídy. |
## Metody

| Metoda | Popis |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Nastavuje měřený veřejný a soukromý klíč. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Získává velikost souboru spotřeby |
| [getConsumptionCredit()](#getConsumptionCredit--) | Získává kredit spotřeby |
| [isMeteredLicensed()](#isMeteredLicensed--) | Kontroluje, zda je měřený licencovaný |
### Metered() {#Metered--}
```
public Metered()
```


Inicializuje novou instanci této třídy.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Nastavuje měřený veřejný a soukromý klíč. Pokud zakoupíte měřenou licenci, při spuštění aplikace by se toto API mělo zavolat; obvykle to stačí. Pokud však stále selhává nahrávání dat o spotřebě a překročí 24 hodin, licence bude nastavena do stavu hodnocení. Aby se taková situace předešla, měli byste pravidelně kontrolovat stav licence; pokud je ve stavu hodnocení, zavolejte toto API znovu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| publicKey | java.lang.String | veřejný klíč |
| privateKey | java.lang.String | soukromý klíč |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Získává velikost souboru spotřeby

**Vrací:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Získává kredit spotřeby

**Vrací:**
double - množství spotřeby
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```


Kontroluje, zda je měřený licencovaný

**Vrací:**
boolean - true nebo false