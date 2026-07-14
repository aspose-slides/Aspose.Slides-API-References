---
title: IOutputSaver
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an output saving service.
type: docs
url: /hi/com.aspose.slides/ioutputsaver/
---```
public interface IOutputSaver
```

आउटपुट सहेजने की सेवा का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [save(String path, IOutputFile outputFile)](#save-java.lang.String-com.aspose.slides.IOutputFile-) | निर्दिष्ट पथ पर आउटपुट फ़ाइल को सहेजता है। |
### save(String path, IOutputFile outputFile) {#save-java.lang.String-com.aspose.slides.IOutputFile-}
```
public abstract void save(String path, IOutputFile outputFile)
```


निर्दिष्ट पथ पर आउटपुट फ़ाइल को सहेजता है।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | फ़ाइल को सहेजने का पथ। |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | आउटपुट फ़ाइल। |