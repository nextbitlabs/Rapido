Rapido.css
----------

Rapido provides a default style for a set of **semantic HTML** elements that you can use to compose your essays. Just write with semantic HTML, without the need to remember any CSS class or JS command.

## Docs

Please have a look at https://nextbitlabs.github.io/Rapido/ for the documentation.

## Motivation

Having your own corner on the web where you can freely share thoughts or technical stuff is still cool, and the popularity of tools like Jekyll or Gatsby proves that. Rapido intervenes there, offering semantic HTML templates for a variety of typical author needs: like header, sections, side notes, references and so on.

The importance of using semantic HTML is a common theme in web development, it is a good idea to use the relevant HTML element for the job. Semantic HTML improves the usability of the code and ensures maximum accessibility.

Rapido has been crafted with the idea that using semantic HTML for your writings *can be easy*. For such a reason Rapido does not make use of CSS classes or Javascript hooks, the author can compose all the different parts of the document with semantic HTML elements, for example adding side notes in paragraphs with the `<small>` element.

```
<article class="rapido">
  <section>
    <h1>...</h1>
    <p>...<small>...</small></p>
  </section>
</article>
```
