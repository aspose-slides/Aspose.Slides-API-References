---
title: Metered
second_title: Riferimento API di Aspose.Slides per Java
description: Fornisce metodi per impostare la chiave misurata.
type: docs
url: /it/com.aspose.slides/metered/
---
**Eredità:**
java.lang.Object
```
public class Metered
```

Fornisce metodi per impostare la chiave misurata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Metered()](#Metered--) | Inizializza una nuova istanza di questa classe. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Imposta la chiave pubblica e privata misurata. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Ottiene la dimensione del file di consumo |
| [getConsumptionCredit()](#getConsumptionCredit--) | Ottiene il credito di consumo |
| [isMeteredLicensed()](#isMeteredLicensed--) | Verifica se la licenza misurata è attiva |
### Metered() {#Metered--}
```
public Metered()
```


Inizializza una nuova istanza di questa classe.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
``` 
public void setMeteredKey(String publicKey, String privateKey)
```


Imposta la chiave pubblica e privata misurata. Se acquisti una licenza misurata, all'avvio dell'applicazione questa API dovrebbe essere chiamata; normalmente è sufficiente. Tuttavia, se il caricamento dei dati di consumo fallisce continuamente e supera le 24 ore, la licenza verrà impostata allo stato di valutazione; per evitare tale situazione, dovresti controllare regolarmente lo stato della licenza e, se è in stato di valutazione, chiamare nuovamente questa API.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| publicKey | java.lang.String | chiave pubblica |
| privateKey | java.lang.String | chiave privata |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Ottiene la dimensione del file di consumo

**Restituisce:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Ottiene il credito di consumo

**Restituisce:**
double - quantità di consumo
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```


Verifica se la licenza misurata è attiva

**Restituisce:**
boolean - vero o falso