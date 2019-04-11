SOURCE
-------
https://github.com/madmaze/pytesseract/

IMPROVEMENTS
-----

- Use tempfile.mkstemp() instead of tempfile.mktemp()
- Support multiple file formats

.. code-block:: python    
    print(pytesseract.image_to_info_files(Image.open('test.png'), extensions = ("txt", "tsv")))