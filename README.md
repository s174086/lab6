# lab6

co, kiedy i jak wykonuje ten workflow (z ilu i jakich jobów i stepów jest złozony, pod wpływem jakiego triggera i w jakim środowisku):

kiedy: gdy zostanie wykonane push lub pull request w docs/**
co: build up document and deploy
jak:
steps: 4
środowisko: ubuntu-latest
nazwy kroków:
- Install sphinx and manim env
- Build document with Sphinx
- Deploy to GitHub pages
  
