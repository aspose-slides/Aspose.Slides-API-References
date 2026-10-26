---
title: IOutputSaver
second_title: Aspose.Slides for Android via Java API Reference
description: 出力保存サービスを表します。
type: docs
url: /ja/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

出力保存サービスを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | 指定されたパスに出力ファイルを保存します。 |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```


指定されたパスに出力ファイルを保存します。

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


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | java.lang.String | ファイルを保存するパス。 |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | 出力ファイル。 |