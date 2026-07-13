---
title: PptOptions
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Fornisce opzioni che controllano come una presentazione viene salvata nel formato PPT.
type: docs
url: /it/com.aspose.slides/pptoptions/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tutte le interfacce implementate:**
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

Fornisce opzioni che controllano come una presentazione viene salvata nel formato PPT.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Rappresenta il GUID della classe dell'oggetto (CLSID) che è memorizzato nella voce della directory radice. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Rappresenta il GUID della classe dell'oggetto (CLSID) che è memorizzato nella voce della directory radice. |
### PptOptions() {#PptOptions--}
```
public PptOptions()
```


### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```


Rappresenta il GUID della classe dell'oggetto (CLSID) che è memorizzato nella voce della directory radice. Può essere utilizzato per l'attivazione COM dell'applicazione del documento. Il valore predefinito è '64818D11-4F9B-11CF-86EA-00AA00B929E8' che corrisponde a 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// imposta CLSID a 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public final void setRootDirectoryClsid(UUID value)
```


Rappresenta il GUID della classe dell'oggetto (CLSID) che è memorizzato nella voce della directory radice. Può essere utilizzato per l'attivazione COM dell'applicazione del documento. Il valore predefinito è '64818D11-4F9B-11CF-86EA-00AA00B929E8' che corrisponde a 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// imposta CLSID a 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.UUID |  |