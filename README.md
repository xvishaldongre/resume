# Vishal's Resume

LaTeX template for my personal resume

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex vishal_dongre_resume.tex
```

### License

Format is MIT but all the data is owned by Vishal Dongre.
