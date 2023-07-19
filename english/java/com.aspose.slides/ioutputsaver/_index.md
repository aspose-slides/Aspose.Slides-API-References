---
title: IOutputSaver
second_title: Aspose.Slides for Java API Reference
description: Represents an output saving service.
type: docs
weight: 954
url: /java/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

Represents an output saving service.
## Methods

| Method | Description |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | Saves the output file to the given path. |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```


Saves the output file to the given path.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Path to save the file to. |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Output file. |

