## Examples of NER/IOB data that can be converted with `spacy convert`

To convert an IOB file to `.spacy` ([`DocBin`](https://spacy.io/api/docbin))
for spaCy v3:

```bash
python -m spacy convert -c iob -s -n 10 -b en_core_web_sm file.iob .
```

See all the `spacy convert` options: https://spacy.io/api/cli#convert

---

The spaCy v2 JSON training files were generated using **spaCy v2** with:

```bash
python -m spacy convert -c iob -s -n 10 -b en file.iob
```

To convert an existing JSON training file to `.spacy` for spaCy v3, convert
with **spaCy v3**:

```bash
python -m spacy convert file.json .
```

---

### About the Maintainer

This project is currently maintained by Mustaq Sohail Shaik.

Mustaq is a Software Engineer with a passion for architecting and deploying intelligent systems that combine machine learning, data engineering, and scalable software design.

You can connect with Mustaq here:
- GitHub: [github.com/dirandodda](https://github.com/dirandodda)
- LinkedIn: [Mustaq Sohail Shaik](https://www.linkedin.com/in/mustaq-sohail-shaik-2224482a8/)
- Email: sohailshaik8255@gmail.com