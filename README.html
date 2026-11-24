<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>CampusConnect | P17 Event Calendar Prototype</title>
<style>
:root{--navy:#172554;--blue:#3156a6;--sky:#eaf1ff;--ink:#172033;--muted:#667085;--line:#e5e9f2;--bg:#f5f7fb;--white:#fff;--green:#16794b;--amber:#9a5b00;--red:#b42318}
*{box-sizing:border-box}body{margin:0;background:var(--bg);color:var(--ink);font:15px/1.5 Inter,ui-sans-serif,system-ui,-apple-system,"Segoe UI",sans-serif}
header{background:linear-gradient(115deg,#172554,#3156a6);color:#fff;padding:22px max(20px,calc((100% - 1120px)/2));}
.top{display:flex;justify-content:space-between;align-items:center;gap:16px;flex-wrap:wrap}.brand{font-size:22px;font-weight:800;letter-spacing:.2px}.brand span{color:#a9c5ff}.tag{font-size:12px;border:1px solid #ffffff55;padding:5px 10px;border-radius:30px}
main{max-width:1120px;margin:24px auto;padding:0 18px}.hero{display:flex;justify-content:space-between;gap:20px;align-items:flex-end;margin-bottom:20px}.hero h1{font-size:clamp(25px,4vw,34px);line-height:1.15;margin:0 0 7px}.hero p{color:var(--muted);margin:0;max-width:670px}.demo{font-size:12px;background:#fff4d6;color:#815000;border:1px solid #f2d58c;padding:8px 12px;border-radius:9px;white-space:nowrap}
.stats{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin:18px 0}.stat,.panel,.event{background:#fff;border:1px solid var(--line);border-radius:14px}.stat{padding:14px 16px}.stat b{display:block;font-size:22px;color:var(--navy)}.stat small{color:var(--muted)}
.toolbar{display:grid;grid-template-columns:1.5fr 1fr 1fr auto;gap:10px;margin:18px 0}.field,select,button{font:inherit}.field,select{width:100%;border:1px solid #d6dce8;border-radius:10px;padding:11px 12px;background:#fff;color:var(--ink)}button{border:0;border-radius:10px;padding:10px 14px;background:var(--blue);color:#fff;font-weight:650;cursor:pointer}button:hover{filter:brightness(.95)}button.secondary{background:#eef2fa;color:#24375f;border:1px solid #dce3f0}button.ghost{background:transparent;color:var(--blue);padding:4px 0}
.layout{display:grid;grid-template-columns:minmax(0,1.65fr) minmax(260px,.8fr);gap:16px;align-items:start}.section-head{display:flex;justify-content:space-between;align-items:center;margin:3px 0 12px}.section-head h2,.panel h2{font-size:18px;margin:0}.muted{color:var(--muted);font-size:13px}
.events{display:grid;gap:11px}.event{padding:15px;display:grid;grid-template-columns:68px 1fr;gap:14px}.datebox{background:var(--sky);border-radius:10px;text-align:center;padding:9px 4px;color:var(--navy);height:max-content}.datebox b{font-size:23px;display:block;line-height:1.15}.datebox small{font-size:11px;text-transform:uppercase;font-weight:750}.event h3{font-size:16px;margin:0 0 4px}.meta{font-size:13px;color:var(--muted);display:flex;flex-wrap:wrap;gap:7px 14px}.desc{font-size:13px;color:#475467;margin:7px 0 9px}.pill{font-size:11px;font-weight:700;background:#edf2ff;color:#3156a6;border-radius:20px;padding:4px 8px;display:inline-block}.event-actions{display:flex;gap:12px;align-items:center;flex-wrap:wrap}.event-actions button{font-size:12px;padding:7px 10px}.panel{padding:16px;margin-bottom:14px}.panel p{font-size:13px;color:var(--muted);margin:7px 0 12px}.clash{border-left:4px solid #e5a000;background:#fff9e9;padding:10px 11px;border-radius:8px;margin:9px 0;font-size:13px}.clash strong{display:block;color:#815000}.empty{padding:28px;text-align:center;border:1px dashed #cbd5e1;border-radius:12px;color:var(--muted);background:#fff}
footer{max-width:1120px;margin:24px auto 36px;padding:0 18px;color:var(--muted);font-size:12px}.modal{position:fixed;inset:0;background:#0b173c88;display:none;align-items:center;justify-content:center;padding:18px;z-index:5}.modal.show{display:flex}.dialog{background:#fff;border-radius:16px;padding:20px;width:min(520px,100%);max-height:90vh;overflow:auto}.dialog h2{margin:0 0 12px}.formgrid{display:grid;grid-template-columns:1fr 1fr;gap:10px}.formgrid label{font-size:12px;color:#475467;display:grid;gap:5px}.formgrid .wide{grid-column:1/-1}.dialog-actions{display:flex;justify-content:flex-end;gap:8px;margin-top:15px}.notice{font-size:12px;background:#f1f5f9;padding:10px;border-radius:9px;color:#475467}
@media(max-width:760px){.layout{grid-template-columns:1fr}.toolbar{grid-template-columns:1fr 1fr}.toolbar input{grid-column:1/-1}.hero{display:block}.demo{display:inline-block;margin-top:12px}.stats{gap:8px}.stat{padding:11px}.stat b{font-size:19px}}
@media(max-width:430px){.toolbar{grid-template-columns:1fr}.toolbar input{grid-column:auto}.stats{grid-template-columns:1fr 1fr}.event{grid-template-columns:55px 1fr;padding:12px}.datebox b{font-size:20px}.formgrid{grid-template-columns:1fr}.formgrid .wide{grid-column:auto}}
</style>
</head>
<body>
<header><div class="top"><div class="brand">Campus<span>Connect</span></div><div class="tag">P17 · Student event discovery demo</div></div></header>
<main>
  <div class="hero"><div><h1>Find events worth showing up for.</h1><p>Explore campus activities in one place. Search by interest, compare dates and times, and help organisers spot possible schedule overlaps.</p></div><div class="demo">DEMO DATA · Not official LPU listings</div></div>
  <div class="stats">
    <div class="stat"><b id="eventCount">6</b><small>Sample events listed</small></div>
    <div class="stat"><b id="categoryCount">5</b><small>Interest categories</small></div>
    <div class="stat"><b id="clashCount">1</b><small>Possible time overlaps</small></div>
  </div>
  <div class="toolbar">
    <input class="field" id="search" placeholder="Search event, club or keyword…" aria-label="Search events">
    <select id="category" aria-label="Filter by category"><option value="">All categories</option><option>Technology</option><option>Culture</option><option>Sports</option><option>Career</option><option>Wellness</option></select>
    <select id="dateFilter" aria-label="Filter by date"><option value="">All dates</option><option value="2026-12-02">2 Dec 2026</option><option value="2026-12-03">3 Dec 2026</option><option value="2026-12-04">4 Dec 2026</option><option value="2026-12-05">5 Dec 2026</option></select>
    <button class="secondary" id="clear">Clear filters</button>
  </div>
  <div class="layout">
    <section>
      <div class="section-head"><h2>Upcoming events</h2><span class="muted" id="resultLabel">Showing all demo events</span></div>
      <div class="events" id="events"></div>
    </section>
    <aside>
      <div class="panel"><h2>Organiser view</h2><p>Check the sample schedule for events that overlap in date and time. This is a simple demonstration, not an approval system.</p><div id="clashes"></div><button id="addEvent">＋ Submit a demo event</button></div>
      <div class="panel"><h2>How to try this prototype</h2><p>1. Search for “coding” or “music”.<br>2. Filter by a category or date.<br>3. Open an event to read its details.<br>4. Review the possible overlaps in Organiser view.<br>5. Submit a sample event and see it appear in the list.</p><div class="notice">All event names, organisers, dates, times and venues below are fictional sample data created only to demonstrate the interface.</div></div>
    </aside>
  </div>
</main>
<footer>CampusConnect · P17 prototype concept. Sample content only; verify real event details with organisers before any live use.</footer>

<div class="modal" id="detailModal"><div class="dialog"><h2 id="detailTitle">Event details</h2><div id="detailBody"></div><div class="dialog-actions"><button class="secondary" id="closeDetail">Close</button></div></div></div>
<div class="modal" id="submitModal"><div class="dialog"><h2>Submit a demo event</h2><p class="muted">This form adds an event to this page only. It does not send data to the university.</p>
<form id="eventForm"><div class="formgrid">
<label class="wide">Event title<input class="field" name="title" required placeholder="e.g. Design Thinking Meetup"></label>
<label>Organiser / club<input class="field" name="organiser" required placeholder="Club name"></label>
<label>Category<select name="category" class="field"><option>Technology</option><option>Culture</option><option>Sports</option><option>Career</option><option>Wellness</option></select></label>
<label>Date<input class="field" name="date" type="date" min="2026-01-01" required></label>
<label>Start time<input class="field" name="start" type="time" required></label>
<label>End time<input class="field" name="end" type="time" required></label>
<label class="wide">Venue<input class="field" name="venue" required placeholder="Venue (demo)"></label>
<label class="wide">Short description<input class="field" name="description" placeholder="What is the event about?"></label>
</div><div class="dialog-actions"><button type="button" class="secondary" id="cancelSubmit">Cancel</button><button type="submit">Add to demo calendar</button></div></form></div></div>

<script>
const events = [
{id:1,title:"Campus Coding Sprint",organiser:"Tech Society (sample)",category:"Technology",date:"2026-12-02",start:"15:00",end:"17:00",venue:"Innovation Hall (sample)",description:"A friendly team coding challenge for students interested in building and problem-solving."},
{id:2,title:"Acoustic Evening",organiser:"Cultural Club (sample)",category:"Culture",date:"2026-12-02",start:"16:00",end:"18:00",venue:"Open Air Stage (sample)",description:"An informal music evening featuring student performances."},
{id:3,title:"Inter-Block Football",organiser:"Sports Council (sample)",category:"Sports",date:"2026-12-03",start:"09:00",end:"11:00",venue:"Main Ground (sample)",description:"A friendly football fixture for campus teams."},
{id:4,title:"Career Skills Workshop",organiser:"Career Forum (sample)",category:"Career",date:"2026-12-04",start:"13:00",end:"14:30",venue:"Seminar Room A (sample)",description:"Practice interview introductions and learn how to present project experience."},
{id:5,title:"Mindful Break Session",organiser:"Wellness Group (sample)",category:"Wellness",date:"2026-12-04",start:"16:00",end:"17:00",venue:"Activity Studio (sample)",description:"A short guided session focused on relaxation and healthy study breaks."},
{id:6,title:"UI/UX Design Jam",organiser:"Design Circle (sample)",category:"Technology",date:"2026-12-05",start:"11:00",end:"13:00",venue:"Creative Lab (sample)",description:"Work in small groups to sketch and share ideas for a simple student-focused interface."}
];
const $=id=>document.getElementById(id);
const fmtDate=d=>new Date(d+"T12:00:00").toLocaleDateString("en-IN",{day:"2-digit",month:"short"});
const fmtTime=t=>{let [h,m]=t.split(":").map(Number);let ap=h>=12?"PM":"AM";return `${(h%12)||12}:${String(m).padStart(2,"0")} ${ap}`};
function overlaps(a,b){return a.date===b.date && a.start < b.end && b.start < a.end}
function getClashes(){let out=[];for(let i=0;i<events.length;i++)for(let j=i+1;j<events.length;j++)if(overlaps(events[i],events[j]))out.push([events[i],events[j]]);return out}
function render(){
 const q=$("search").value.toLowerCase(),cat=$("category").value,date=$("dateFilter").value;
 const filtered=events.filter(e=>(!q||[e.title,e.organiser,e.description,e.venue].join(" ").toLowerCase().includes(q))&&(!cat||e.category===cat)&&(!date||e.date===date));
 $("events").innerHTML=filtered.length?filtered.sort((a,b)=>(a.date+a.start).localeCompare(b.date+b.start)).map(e=>`<article class="event"><div class="datebox"><b>${fmtDate(e.date).split(" ")[0]}</b><small>${fmtDate(e.date).split(" ")[1]}</small></div><div><h3>${esc(e.title)}</h3><div class="meta"><span>${esc(e.category)}</span><span>${fmtTime(e.start)}–${fmtTime(e.end)}</span><span>${esc(e.venue)}</span></div><p class="desc">${esc(e.description||"No description provided.")}</p><div class="event-actions"><span class="pill">${esc(e.organiser)}</span><button class="secondary" onclick="showDetails(${e.id})">View details</button></div></div></article>`).join(""):`<div class="empty">No events match those filters. Try another search or clear the filters.</div>`;
 $("resultLabel").textContent=`Showing ${filtered.length} of ${events.length} demo events`;
 $("eventCount").textContent=events.length;
 $("categoryCount").textContent=new Set(events.map(e=>e.category)).size;
 const clashes=getClashes();$("clashCount").textContent=clashes.length;
 $("clashes").innerHTML=clashes.length?clashes.map(([a,b])=>`<div class="clash"><strong>Possible overlap · ${fmtDate(a.date)}</strong>${esc(a.title)} (${fmtTime(a.start)}–${fmtTime(a.end)})<br>and ${esc(b.title)} (${fmtTime(b.start)}–${fmtTime(b.end)})</div>`).join(""):`<p>No overlapping sample events detected.</p>`;
}
function esc(s){return String(s).replace(/[&<>"']/g,c=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#39;"}[c]))}
window.showDetails=id=>{let e=events.find(x=>x.id===id);if(!e)return;$("detailTitle").textContent=e.title;$("detailBody").innerHTML=`<p><b>Category:</b> ${esc(e.category)}</p><p><b>Organiser:</b> ${esc(e.organiser)}</p><p><b>Date:</b> ${fmtDate(e.date)} 2026</p><p><b>Time:</b> ${fmtTime(e.start)}–${fmtTime(e.end)}</p><p><b>Venue:</b> ${esc(e.venue)}</p><p>${esc(e.description)}</p><div class="notice">This is fictional demonstration content, not a confirmed campus event.</div>`;$("detailModal").classList.add("show")};
["search","category","dateFilter"].forEach(id=>$(id).addEventListener(id==="search"?"input":"change",render));
$("clear").onclick=()=>{$("search").value="";$("category").value="";$("dateFilter").value="";render()};
$("closeDetail").onclick=()=>$("detailModal").classList.remove("show");
$("addEvent").onclick=()=>$("submitModal").classList.add("show");
$("cancelSubmit").onclick=()=>$("submitModal").classList.remove("show");
$("eventForm").onsubmit=e=>{e.preventDefault();let f=new FormData(e.target);let start=f.get("start"),end=f.get("end");if(end<=start){alert("End time must be later than start time.");return}events.push({id:Math.max(...events.map(x=>x.id))+1,title:f.get("title"),organiser:f.get("organiser"),category:f.get("category"),date:f.get("date"),start,end,venue:f.get("venue"),description:f.get("description")});e.target.reset();$("submitModal").classList.remove("show");render();alert("Demo event added to this page. It has not been submitted to LPU or stored online.")};
render();
</script>
</body></html>
