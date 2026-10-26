---
title: IPortionFormat
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Questa classe contiene le proprietà di formattazione della porzione di testo.
type: docs
url: /it/com.aspose.slides/iportionformat/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

Questa classe contiene le proprietà di formattazione della porzione di testo. A differenza di [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), tutte le proprietà di questa classe sono scrivibili.

--------------------

Questa classe è usata per restituire e manipolare le proprietà di formattazione della porzione di testo definite per la porzione specifica. Ciò significa che non viene applicata alcuna ereditarietà durante il recupero dei valori, quindi nella maggior parte dei casi otterrai valori che significano "non definito".

Per ottenere i valori dei parametri di formattazione efficaci, incluse le proprietà ereditate, è necessario utilizzare il metodo [getEffective](../../com.aspose.slides/iportionformat\#getEffective) che restituisce un'istanza di [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Restituisce o imposta l'identificatore del segnalibro. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Restituisce o imposta l'identificatore del segnalibro. |
| [getSmartTagClean()](#getSmartTagClean--) | Determina se il tag intelligente deve essere pulito. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Determina se il tag intelligente deve essere pulito. |
| [getEffective()](#getEffective--) | Recupera i dati di formattazione della porzione efficace con l'ereditarietà applicata. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

Restituisce o imposta l'identificatore del segnalibro. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

Restituisce o imposta l'identificatore del segnalibro. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Determina se il tag intelligente deve essere pulito. Nessuna ereditarietà applicata. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

Determina se il tag intelligente deve essere pulito. Nessuna ereditarietà applicata. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

Recupera i dati di formattazione della porzione efficace con l'ereditarietà applicata.

**Restituisce:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - Un [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).