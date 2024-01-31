



# seed


**seed for pathology atlas repositories**






```
r language seed, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis bitki tohumu, yiyecek artığı TR, echo = (language == "TR")
## seed - bitki tohumu, yiyecek artığı {#sec-seed }
```


```
asis seed, food remnant  EN, echo = (language == "EN")
## seed - seed, food remnant  {#sec-seed }
```






```
r seed screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/thumbnail_seed-HE.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/seed/HE.html",
  file = "./screenshots/thumbnail_seed-HE.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/seed/HE.html](https://images.patolojiatlasi.com/seed/HE.html)





```
asis, echo = (language == "TR")

**bitki tohumu, yiyecek artığı**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/thumbnail_seed-HE.png){width="25%"}](https://images.patolojiatlasi.com/seed/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/seed/HE.html)
```

```
asis, echo = (language == "EN")

**seed, food remnant **

[![Click for Full Screen WSI](./screenshots/thumbnail_seed-HE.png){width="25%"}](https://images.patolojiatlasi.com/seed/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/seed/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/seed/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/seed/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

bitki tohumu, yiyecek artığı

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

seed, food remnant 

:::

```









:::::












