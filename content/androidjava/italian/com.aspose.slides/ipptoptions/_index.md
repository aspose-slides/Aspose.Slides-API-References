---
title: IPptOptions
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Fornisce opzioni che controllano come una presentazione viene salvata in formato PPT.
type: docs
url: /it/com.aspose.slides/ipptoptions/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

Fornisce opzioni che controllano come una presentazione viene salvata in formato PPT.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Rappresenta il GUID della classe dell'oggetto (CLSID) che è memorizzato nella voce della directory principale. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Rappresenta il GUID della classe dell'oggetto (CLSID) che è memorizzato nella voce della directory principale. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```

Rappresenta il GUID della classe dell'oggetto (CLSID) che è memorizzato nella voce della directory principale. Può essere usato per l'attivazione COM dell'applicazione del documento. Il valore predefinito è '64818D11-4F9B-11CF-86EA-00AA00B929E8' che corrisponde a 'Microsoft Powerpoint.Slide.8'.

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
public abstract void setRootDirectoryClsid(UUID value)
```

Rappresenta il GUID della classe dell'oggetto (CLSID) che è memorizzato nella voce della directory principale. Può essere usato per l'attivazione COM dell'applicazione del documento. Il valore predefinito è '64818D11-4F9B-11CF-86EA-00AA00B929E8' che corrisponde a 'Microsoft Powerpoint.Slide.8'.

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