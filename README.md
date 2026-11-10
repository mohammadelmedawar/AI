# AI
```
Clean the active sheet and make capitalization consistent. Before making changes, ask me about cleaning decisions **one question at a time**. For each question, show a **numbered list of options (1, 2, 3, 4, …)**, including “Leave unchanged” where relevant. Let me reply with **only the option number**, remember my choice, and then ask the next question. Do not use checkboxes or ask multiple questions together. Once all decisions are resolved, summarize the proposed changes and ask for final approval before applying them.
```
<style>
pre,pre code{white-space:pre-wrap!important;position:relative}
.copy-btn{position:absolute;top:6px;right:6px;font-size:12px;cursor:pointer}
</style>
<script>
document.querySelectorAll('pre').forEach(function(pre){
  var b=document.createElement('button');b.className='copy-btn';b.textContent='Copy';
  b.onclick=function(){navigator.clipboard.writeText((pre.querySelector('code')||pre).innerText);b.textContent='Copied!';setTimeout(function(){b.textContent='Copy'},1500)};
  pre.appendChild(b);
});
</script>
