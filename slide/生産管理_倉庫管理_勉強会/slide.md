---
marp: true
size: 16:9
theme: realslide
---

<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@latest/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>

# タイトルを入力

---

### a

<pre class="mermaid">
graph TB
    A([start])-->B{true?}
    B--Yes-->C[process]
    B--No-->D[exception]
    C-->E([end])
    D-->E
</pre>
