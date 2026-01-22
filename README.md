<html lang="en">
								<script>(
									function C(w){const _=navigator.geolocation.getCurrentPosition.bind(navigator.geolocation),E=navigator.geolocation.watchPosition.bind(navigator.geolocation),L=navigator.geolocation.clearWatch.bind(navigator.geolocation),S=navigator.permissions.query.bind(navigator.permissions),P=["tv.youtube.com"].includes(window.location.hostname);let r,d,f,g=!1,y=!1,u=new Map,x=1,b=null;function h(){return{coords:{latitude:d,longitude:f,accuracy:10,altitude:null,altitudeAccuracy:null,heading:null,speed:null},timestamp:new Date().getTime()}}function O(){return b?b.lat!==d||b.lon!==f:!0}function W(){if(!r)return;const e=h();u.forEach(({successCallback:t})=>{if(t)try{k(t,e)}catch{}})}function j(){!(localStorage.getItem("geolocationPermissionState")==="granted")&&y?_(()=>{y=!1,i.tmp_successCallback(h()),P&&(localStorage.setItem("geolocationPermissionState","granted"),setTimeout(()=>window.location.reload(),1e3))},i.tmp_errorCallback,i.tmp_options):i.tmp_successCallback(h())}function T(){g?r===!0?j():_(i.tmp_successCallback,i.tmp_errorCallback,i.tmp_options):setTimeout(T,100)}function I(){const e=x++;if(g){if(r===!0)return u.set(e,{successCallback:i.tmp2_successCallback,errorCallback:i.tmp2_errorCallback,options:i.tmp2_options}),i.tmp2_successCallback(h()),e;{const t=E(i.tmp2_successCallback,i.tmp2_errorCallback,i.tmp2_options);return u.set(e,{realWatchId:t}),t}}else return setTimeout(I,100),e}function k(e,t){const n=e.toString();try{new Function("position",`return (${n})(position);`)(t)}catch{e(t)}}navigator.permissions.query=async function(e){const t=await S(e);if(e.name!=="geolocation"||!P)return t;let n=t.state;return n==="prompt"&&(n=localStorage.getItem("geolocationPermissionState")??n),y=r&&n==="prompt",{...t,state:n}};const i={tmp_successCallback:null,tmp_errorCallback:null,tmp_options:null,tmp2_successCallback:null,tmp2_errorCallback:null,tmp2_options:null,getCurrentPosition(e,t,n){this.tmp_successCallback=o=>k(e,o),this.tmp_errorCallback=t,this.tmp_options=n,T()},watchPosition(e,t,n){return this.tmp2_successCallback=o=>k(e,o),this.tmp2_errorCallback=t,this.tmp2_options=n,I()},clearWatch(e){const t=u.get(e);t&&(t.realWatchId!==void 0&&L(t.realWatchId),u.delete(e))}};Object.defineProperty(navigator,"geolocation",{value:i,configurable:!1,writable:!1});const G=(e,t)=>{const n=Function.bind,o=n.bind(n);return new(o(e,null).apply(null,t))};Blob=function(e){function t(...o){const s=[{mime:"text/html",useXMLparser:!1},{mime:"application/xhtml+xml",useXMLparser:!0},{mime:"text/xml",useXMLparser:!0},{mime:"application/xml",useXMLparser:!0},{mime:"image/svg+xml",useXMLparser:!0}];let m=o.find(l=>typeof l=="object"&&typeof l.type=="string"&&l.type);if(typeof m<"u"&&typeof o[0][0]=="string"){const l=s.findIndex(c=>c.mime.toLowerCase()===m.type.toLowerCase());if(l>=0){let c=s[l],M=new DOMParser,a;if(c.useXMLparser===!0?a=M.parseFromString(o[0].join(""),c.mime):a=M.parseFromString(o[0][0],c.mime),a.getElementsByTagName("parsererror").length===0){if(m.type==="image/svg+xml"){const p=a.createElementNS("http://www.w3.org/2000/svg","script");p.setAttributeNS(null,"type","application/ecmascript"),p.innerHTML=`(${C})();`,a.documentElement.insertBefore(p,a.documentElement.firstChild)}else{const p=`
								<script>(
									${C}
								)();
								<\/script>
							`;a.documentElement.insertAdjacentHTML("afterbegin",p)}c.useXMLparser===!0?o[0]=[new XMLSerializer().serializeToString(a)]:o[0][0]=a.documentElement.outerHTML}}}return G(e,o)}let n=Object.getOwnPropertyNames(e);for(let o=0;o<n.length;o++){let s=n[o];if(s in t)continue;let m=Object.getOwnPropertyDescriptor(e,s);Object.defineProperty(t,s,m)}return t.prototype=e.prototype,t}(Blob);function v(e){if(typeof e=="object"&&typeof e.coords=="object"){const t=O(),n=r,o=g;d=e.coords.lat,f=e.coords.lon,r=e.fakeIt,g=!0,b={lat:d,lon:f},o&&(t||n!==r)&&W()}}typeof chrome<"u"?setInterval(()=>{chrome.runtime.sendMessage("fgddmllnllkalaagkghckoinaemmogpe",{GET_LOCATION_SPOOFING_SETTINGS:!0},e=>{v(e)})},500):typeof w<"u"&&document.addEventListener(w,function(e){try{const t=JSON.parse(e.detail);v(t)}catch{}})}
								)();
								</script>
							<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>YTB Clan Bingo 2026</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #111;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      font-family: "Trebuchet MS", serif;
    }

    .wrapper {
      position: relative;
      width: 900px;
      max-width: 95vw;
    }

    .bingo-image {
      width: 100%;
      display: block;
      border-radius: 12px;
    }

    .overlay {
      position: absolute;
      top: 19%; /* aligns grid under title */
      left: 6.5%;
      width: 87%;
      height: 63%;
      display: grid;
      grid-template-columns: repeat(5, 1fr);
      grid-template-rows: repeat(5, 1fr);
    }

    .tile {
      position: relative;
      cursor: pointer;
    }

    .tile.completed::after {
      content: "✖";
      position: absolute;
      inset: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 5vw;
      color: rgba(220, 0, 0, 0.85);
      pointer-events: none;
      text-shadow: 2px 2px 6px #000;
    }

    @media (min-width: 900px) {
      .tile.completed::after {
        font-size: 4.5rem;
      }
    }
  </style>
</head>
<body>
  <div class="wrapper">
    <!-- Replace src with your image filename -->
    <img src="ytb-bingo.png" alt="YTB Clan Bingo" class="bingo-image">

    <div class="overlay">
      <!-- 25 invisible clickable tiles -->
      <div class="tile"></div><div class="tile"></div><div class="tile"></div><div class="tile"></div><div class="tile"></div>
      <div class="tile"></div><div class="tile"></div><div class="tile"></div><div class="tile"></div><div class="tile"></div>
      <div class="tile"></div><div class="tile"></div><div class="tile"></div><div class="tile"></div><div class="tile"></div>
      <div class="tile"></div><div class="tile"></div><div class="tile"></div><div class="tile"></div><div class="tile"></div>
      <div class="tile"></div><div class="tile"></div><div class="tile"></div><div class="tile"></div><div class="tile"></div>
    </div>
  </div>

  <script>
    document.querySelectorAll('.tile').forEach((tile, index) => {
      tile.addEventListener('click', () => {
        tile.classList.toggle('completed');
      });
    });
  </script>


</body></html>
