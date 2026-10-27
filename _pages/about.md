---
layout: single
permalink: /
title: ""
excerpt: ""
author_profile: false
redirect_from:
  - /about/
  - /about.html
  - /research/
  - /research.html
---

<style>
.home-intro{display:grid;grid-template-columns:minmax(220px, 360px) minmax(0, 1fr);gap:3.5rem;align-items:start;max-width:1100px;margin:1.5rem auto 0}
.home-intro__portrait{aspect-ratio:1 / 1;overflow:hidden;border-radius:1rem}
.home-intro__portrait img{display:block;width:100%;height:100%;object-fit:cover}
.home-intro__content h1{margin:0 0 0.5rem;font-size:2.35rem;line-height:1.05}
.home-intro__content p{max-width:44rem;margin-bottom:1.35rem;font-size:1.08rem;line-height:1.55}
.home-intro__content .home-intro__role{margin-bottom:2.1rem;font-size:1rem;line-height:1.45}
.home-intro__content a{color:#000;text-decoration:underline}
@media (min-width: 57.8125em){.page:has(.home-intro){width:100%;float:right;margin-right:0;padding-left:0%;padding-right:0%}
}
@media (max-width: 48em){.home-intro{grid-template-columns:1fr;gap:2rem;max-width:34rem}
.home-intro__portrait{width:min(100%, 360px)}
}
.jmp{margin:0 0 1.5rem}
.home-intro__content .jmp__label{margin:0 0 0.25rem;font-size:0.8rem;letter-spacing:0.05em;text-transform:uppercase;color:#7a8288}
.jmp .jmp__title,.home-intro__content .jmp__title{margin:0 0 0.5rem;font-weight:bold}
.jmp__abstract summary{display:inline-block;padding:0.3em 0.9em;border:1px solid #bdc1c4;border-radius:4px;font-family:-apple-system,".SFNSText-Regular","San Francisco","Roboto","Segoe UI","Helvetica Neue","Lucida Grande",Arial,sans-serif;font-size:0.8rem;cursor:pointer;list-style:none;user-select:none}
.jmp__abstract summary::-webkit-details-marker{display:none}
.jmp__abstract summary::after{content:" \25BE"}
.jmp__abstract[open] summary::after{content:" \25B4"}
.jmp__abstract summary:hover{background-color:#f2f3f3}
.jmp__abstract p,.home-intro__content .jmp__abstract p{margin:0.75rem 0 0;font-size:0.95rem;line-height:1.55}
.home-research{display:grid;grid-template-columns:minmax(220px, 360px) minmax(0, 1fr);column-gap:3.5rem;max-width:1100px;margin:3.5rem auto 0;padding-top:2.5rem;border-top:1px solid #f2f3f3}
.home-research h2{grid-column:1;margin:0;padding:0;border:0;font-size:1.15rem}
.home-research>:not(h2){grid-column:2}
.home-research ul{margin:0 0 2.25rem;padding:0;list-style:none}
.home-research li{margin-bottom:1.1rem;color:#494e52;font-size:0.95rem;line-height:1.5}
.home-research li>strong:first-child{display:block;margin-bottom:0.15rem;color:#000;font-size:1.05rem}
.home-research a{color:#000;text-decoration:underline}
@media (max-width: 48em){.home-research{display:block;max-width:34rem}
.home-research h2{margin-bottom:1rem}
}

.home-intro__content .jmp__coauthors{margin:0 0 0.6rem;font-size:0.95rem}

.home-research li>p{margin:0 0 0.6rem}


</style>

<section class="home-intro" aria-labelledby="home-intro-name">
  <div class="home-intro__portrait">
    <img src="{{ '/images/profile.png' | relative_url }}" alt="Renata Abbott">
  </div>

  <div class="home-intro__content">
    <h1 id="home-intro-name">Renata Abbott</h1>
    <p class="home-intro__role">PhD Candidate<br>Department of Economics, UC San Diego</p>

    <p><strong>I am on the 2026–2027 Economics Job Market.</strong></p>

    <p class="jmp__label">Job Market Paper</p>
    <div class="jmp">
      <p class="jmp__title"><a href="{{ '/files/Abbott_JMP.pdf' | relative_url }}">Multiproduct Firm Growth and Production Networks</a></p>
      <p class="jmp__coauthors">with Marco Rojas</p>
      <details class="jmp__abstract" id="abstract-mpfg">
        <summary>Abstract</summary>
        <p>Why are some suppliers much larger than others? We ask how two decisions, how many products to sell and how many buyers to serve, interact and shape differences in supplier size. Using the universe of firm-to-firm transactions in Chile, we find that within suppliers, a 10\% increase in buyers is associated with a 5.6\% increase in product scope. We develop a model of multiproduct suppliers in a production network with two channels linking these choices: amortization of product-adoption costs across buyers, and matching, whereby more buyers create more opportunities to sell each product. Because buyers typically purchase only a few of a supplier's products and differ in which ones they buy, matching accounts for most of this co-movement: more buyers mainly help existing products find a buyer. In the model, spillovers run primarily from buyers to products: halving buyer-acquisition costs raises product scope by 14\%, while halving product-adoption costs raises the buyer base by only 2\%. Buyer reach alone reproduces about 89\% of the dispersion in firm sales, compared with 53\% for product scope alone. Product scope mainly amplifies differences generated through buyer networks.</p>
      </details>
    </div>

    <p class="home-intro__bio">My primary fields are macroeconomics and trade.</p>
    <p>My CV is <a href="{{ '/files/Abbott_Renata_CV.pdf' | relative_url }}">here</a>. You can reach me at <a href="mailto:rabbottnavarrete@ucsd.edu">rabbottnavarrete@ucsd.edu</a>.</p>
  </div>
</section>

<section class="home-research" id="research" aria-labelledby="work-in-progress-heading">
  <h2 id="work-in-progress-heading">Work in Progress</h2>
  <ul>
    <li>
      <strong>Trade Credit, Liquidity, and Network Contagion: Evidence from Transaction-Level Data</strong>
      <p>with Patricio Toro and Levent Altinoglu</p>
      <details class="jmp__abstract" id="abstract-tc">
        <summary>Abstract</summary>
        <p>We investigate the role of trade credit (TC) and input-output (I-O) linkages in allocating liquidity and propagating shocks across a network of firms. We use two natural experiments and supervisory, transaction-level data on the universe of firms in Chile to identify demand and financial shocks to firms, and estimate how these shocks propagate differently through the supply chain depending on the use of trade credit. Guided by a general model of trade credit, we decompose these estimated effects into two channels: a trade credit channel and an input-output channel. Our preliminary results indicate that while trade credit does not propagate demand shocks, it propagates financial shocks upstream, suggesting that trade credit serves to reallocate liquidity in the input-output network. However, because trade contracts are sticky, firms respond to financial shocks not by borrowing more or less from a given supplier, but rather by substituting inputs across suppliers who offer different trade credit terms. These results suggest that, due to frictions to adjusting trade credit contracts, financial shocks temporarily alter the structure of the input-output network.</p>
      </details>
    </li>
  </ul>
</section>
