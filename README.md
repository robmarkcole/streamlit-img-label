# Streamlit Image Labelling - Blog post

streamlit-img-label is a graphical image annotation tool using streamlit. Annotations are saved as XML files in PASCAL VOC format.

## Installation

In your python virtual environment, run:

```sh
pip install streamlit-img-label
```

## Example
```sh
python app.py
```

## Demo
![Demo](asset/st_img_label.gif)

## Reference

- [streamlit-cropper](https://github.com/turner-anderson/streamlit-cropper)

## Dev

* `python3 -m venv venv`
* `source venv/bin/activate`
* `(venv) pip install -r requirements.txt` or `(venv) pip install -e .`
* `(venv) streamlit run app.py`