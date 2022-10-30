layout: true
  
<div class="my-header"></div>

<div class="my-footer">
  <table>
    <tr>
      <td style="text-align:right">Sächsische Landesbibliothek – Staats- und Universitätsbibliothek</td>
      <td>Date</td>
      <td style="text-align:right"><a href="https://www.slub-dresden.de/">www.slub-dresden.de</a></td>
    </tr>
    <tr>
      <td style="text-align:right">Referat Open Science</td>
      <td />
    </tr>
  </table>
</div>

<div class="my-title-footer">
  <table>
    <tr>
      <td style="text-align:left"><b>Kay-Michael Würzner</b></td>
    </tr>
    <tr>
      <td style="text-align:left">Referat Open Science</td>
    </tr>
    <tr>
      <td style="font-size:8pt"><b>1. November 2022</b></td>
    </tr>
    <tr>
      <td style="font-size:8pt">Ringvorlesung <i>Digital Humanities</i></td>
    </tr>
  </table>
</div>

---

class: title-slide
count: false

# Vom Textobjekt über digitale Volltexte zu Forschungsdaten
## Digitalisierung, Annotation und Analyse

---

# Überblick

- vom Textobjekt zum maschinenlesbaren Volltext
    + Optical Character Recognition
    + Repräsentationen digitaler Texte
- vom maschinenlesbaren Volltext zum Forschungsdatum in der quantitativen Korpuslinguistik
    + automatische Annotation
    + quantitative Textanalyse

---

class: part-slide
count: false

# Etappe 1: vom Textobjekt zum maschinenlesbaren Volltext

---

# Belege als Forschungsgrundlage

.cols[
.fourty[
- empirische Forschung → Belege
]
.sixty[
]
]

---

count: false

# Belege als Forschungsgrundlage

.cols[
.fourty[
- empirische Forschung → Belege
]
.sixty[
<p style="margin-top:-20px">
<img src="https://upload.wikimedia.org/wikipedia/commons/f/f3/Gneis2.jpg" height="500px" />
</p>
]
]

---

count: false

# Belege als Forschungsgrundlage

.cols[
.fourty[
- empirische Forschung → Belege
]
.sixty[
<p style="margin-top:-20px">
<img src="https://upload.wikimedia.org/wikipedia/commons/6/62/Gro%C3%9Fe_Faustkeile.JPG" height="500px" />
</p>
]
]

---

count: false

# Belege als Forschungsgrundlage

.cols[
.fourty[
- empirische Forschung → Belege
]
.sixty[
<p style="margin-top:-20px">
<img src="https://upload.wikimedia.org/wikipedia/commons/3/39/Ebstorfer-stich2.jpg" height="500px" />
</p>
]
]

---

count: false

# Belege als Forschungsgrundlage

.cols[
.fourty[
- empirische Forschung → Belege
]
.sixty[
<p style="margin-top:-20px">
<img src="https://upload.wikimedia.org/wikipedia/commons/9/9f/Codex_Manesse_127r.jpg" height="500px" />
</p>
]
]

---

count: false

# Belege als Forschungsgrundlage

.cols[
.fourty[
- empirische Forschung → Belege
- Textdokumente als prominente Belegquelle
    + Linguistik
    + Geschichte
    + Recht
    + Philosophie
    + ...
]
.sixty[
<p style="margin-top:-20px">
<img src="https://upload.wikimedia.org/wikipedia/commons/9/9f/Codex_Manesse_127r.jpg" height="500px" />
</p>
]
]

---

# Textdokumente als Belegquelle

- Vorteile
    + in großem Umfang verfügbar
    + systematisch gesammelt
    + einfach reproduzierbar
    + leicht zu lesen
    + leicht zu digitalisieren
- *Korpora*: repräsentative Erfassung einer Sprache, eines Sprachstandes, eines speziellen Ausschnitts einer Sprache
    + Referenzkorpora: British National Corpus, Deutsches Textarchiv
    + Spezialkorpora
        * *childLex* [(Schroeder et al. 2014)](https://link.springer.com/article/10.3758/s13428-014-0528-1)
        * Internetblogs [(Barbaresi und Würzner 2015)](https://edoc.bbaw.de/opus4-bbaw/frontdoor/index/index/docId/2330)
        * *Berliner Wendekorpus* [(Dittmar und Paul 2019)](https://ids-pub.bsz-bw.de/frontdoor/deliver/index/docId/9349/file/Dittmar_Paul_Sprechen_im_Umbruch_2019.pdf)

---

# Dokumenttypen

- **Problem**: Digitalisierung ↛ Texterfassung

---

# Fokus: Texterfassung per OCR

.cols[
.sixty[
- Bilderfassung ≠ Texterfassung
- **O**ptical **C**haracter **R**ecognition: Automatische Erfassung von Text in Bildern
- ursprünglich begrenzt auf Zeichenerkennung
- heute häufig Synonym für den gesamten Texterfassungsprozess
  + Bildvorverarbeitung
  + Layoutanalyse (OLR)
  + Zeilenerkennung
  + ...
]
.fourty[
<center><img src="https://upload.wikimedia.org/wikipedia/commons/9/9f/Codex_Manesse_127r.jpg" /></center>
]
]

---

# Komponenten eines einfachen OCR-Workflows

.cols[
.fifty[
]
.fourty[
<p style="margin-top:-80px">
<img src="img/grenzboten_raw.svg" />
</p>
]
]

---

count: false

# Komponenten eines einfachen OCR-Workflows

.cols[
.fifty[
- Bildvorverarbeitung
]
.fourty[
<p style="margin-top:-80px">
<img src="img/grenzboten_raw.svg" />
</p>
]
]

---

count: false

# Komponenten eines einfachen OCR-Workflows

.cols[
.fifty[
- Bildvorverarbeitung
]
.fourty[
<p style="margin-top:-80px">
<img src="img/grenzboten_opt.svg" />
</p>
]
]

---

count: false

# Komponenten eines einfachen OCR-Workflows

.cols[
.fifty[
- Bildvorverarbeitung
- Layoutanalyse
]
.fourty[
<p style="margin-top:-80px">
<img src="img/grenzboten_opt.svg" />
</p>
]
]

---

count: false

# Komponenten eines einfachen OCR-Workflows

.cols[
.fifty[
- Bildvorverarbeitung
- Layoutanalyse
]
.fourty[
<p style="margin-top:-80px">
<img src="img/grenzboten_struct.svg" />
</p>
]
]

---

count: false

# Komponenten eines einfachen OCR-Workflows

.cols[
.fifty[
- Bildvorverarbeitung
- Layoutanalyse
- Texterkennung
]
.fourty[
<p style="margin-top:-80px">
<img src="img/grenzboten_struct.svg" />
</p>
]
]

---

count: false

# Komponenten eines einfachen OCR-Workflows

.cols[
.fifty[
- Bildvorverarbeitung
- Layoutanalyse
- Texterkennung
]
.fourty[
<p style="margin-top:-80px">
<img src="img/grenzboten_text.svg" />
</p>
]
]

---

class: part-slide
count: false

# Etappe 2: vom maschinenlesbaren Volltext zum Forschungsdatum in der quantitativen Korpuslinguistik

---

class: part-slide
count: false

# Schlüsselbegriffe und Empfehlungen

---

class: part-slide

# Vielen Dank für Ihre Aufmerksamkeit!

<center>
<a href="https://wrznr.github.io/ringvorlesung-dh-2022/">wrznr.github.io/ringvorlesung-dh-2022</a>
</center>
