---
title: IOutputSaver
second_title: Aspose.Slides for Android via Java API Reference
description: 表示輸出儲存服務。
type: docs
url: /zh-hant/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

表示輸出儲存服務。
## 方法

| 方法 | 說明 |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | 將輸出檔案儲存至指定路徑。 |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```

將輸出檔案儲存至指定路徑。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | java.lang.String | 檔案要儲存的路徑。 |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | 輸出檔案。 |