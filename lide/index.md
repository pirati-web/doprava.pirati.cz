---
layout: default
title: Tým Doprava Pirátské strany
description:  Tým resortu Doprava Pirátské strany
keywords: doprava, odbor, piráti, pirátky, příznivci
---
<div class="row o-section-block ">
    <div class="medium-12 large-12 columns">
      
        <section class="o-section">
        
            <div class="o-section-inner">
              
                <main class="o-section-block">
                
                    <div class="c-BasicPage">
                        <div class="c-BasicPage-content">
 
                                  <a href="#garant" ><h3>VEDOUCÍ RESORTU DOPRAVA - KANDIDÁT NA MINISTRA</h3></a>
                                    <div id="garant"  >
                                        {% assign team = site.people | where_exp:"item","item.categories contains 'garant'" | sort:"ordgarant" %}
                                        {% include people/list-2col.html param=team %}
                                    </div>

   									<br><br><hr><hr>
                                    <a href="#euparlament" ><h3>KONTAKTNÍ OSOBA A MLUVČÍ RESORTU</h3></a>
                                    <div id="euparlament"  >
                                        {% assign team = site.people | where_exp:"item","item.categories contains 'kontakt'" | sort:"ordkontakt" %}
                                        {% include people/list-2col.html param=team %}
                                    </div>
 
   									<br><br><hr><hr>
                                    <a href="#zoexpert"><h3>EXPERTI A PORADCI RESORTU </h3></a>
                                    
                                      <div id="expert" >
                                        <div   >
                                            {% assign team = site.people | where_exp:"item","item.categories contains 'expert-doprava'" %}
                                            {% include people/list-2col.html param=team %}
                                        </div>                                    
                                      </div>  
  
                          </div> 
   
                       </div>                         
                    </main>   
                        
               </div>   
           		   
         </section>    
         
    </div>   

</div> 