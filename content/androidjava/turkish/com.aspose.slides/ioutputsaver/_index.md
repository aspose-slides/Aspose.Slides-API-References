---
title: IOutputSaver
second_title: Aspose.Slides for Android via Java API Reference
description: Çıktı kaydetme hizmetini temsil eder.
type: docs
url: /tr/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```


Çıktı kaydetme hizmetini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | Çıktı dosyasını verilen yola kaydeder. |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```


Çıktı dosyasını verilen yola kaydeder.

--------------------

> ```
> Saving into the FileStream implementation example:
>  
>  public void save(String path, IOutputFile outputFile)
>  {
>      FileOutputStream stream = new FileOutputStream(path);
>      try {
>          outputFile.write(stream);
>      } catch (IOException e) {
>      } finally {
>          if (stream != null) stream.close();
>      }
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | java.lang.String | Dosyanın kaydedileceği yol. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Çıktı dosyası. |