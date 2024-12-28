---
title: Draadloos
author: Riemer Palstra
type: post
date: 2005-12-30T08:06:53+00:00
url: /2005/12/30/draadloos
dsq_thread_id:
  - 796568399
categories:
  - Technostuff

---
[Het meisje][1] wilde nu ook maar eens FreeBSD op [de laptop][2]. Alleen Wi-Fi aan de praat krijgen is dan lastig, met een cheapass [Am1772][3] kaartje. Geen nood, want er zijn kant en klare instructies van heer [Peter van D][4].! &#8230; alleen wilde dat onder FreeBSD 6.0 niet geheel automagisch werken. Het kan tegenwoordig dus zelfs nog makkelijker: pak de .inf en .sys van de CD, draai [ndisgen][5], et voila: daar is je kant en klare loadable kernel module.

 [1]: http://www.distels.com/
 [2]: http://www1.us.dell.com/content/products/productdetails.aspx/inspn_2200?c=us&cs=22&l=en&s=dfh
 [3]: http://www.amd.com/us-en/Corporate/VirtualPressRoom/0,,51_104_543~56851,00.html
 [4]: http://blog.dataloss.nl/perma/freebsd-ndis-wrapper
 [5]: http://www.freebsd.org/cgi/man.cgi?query=ndisgen&sektion=8&manpath=FreeBSD+6.0-RELEASE