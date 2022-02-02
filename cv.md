### martynas dargis
###### Email: martynas.dargis@gmail.com
###### Phone: +37069463594
_I was doing freelancing jobs for almost 1 year, with HTML/CSS and JS. My main task was designing and making the website functional. After the website was done, I would work on SEO. It was a good experience however we were using PHP, and I wanted to learn more modern ways of doing projects. 
My goals are to work in a business-orientated environment using best practices. I want to learn how to write clean code, test it and deploy it. Improve my skill set, learn to use Angular and new tools that will help me with my work._
###### My skills: PHP, HTML, CSS, SEO, Communication, Design
```
<?php
$sklypas['items'] = array (
    array (
        'adresas' => 'razetų 11',
        'statusas'  => '1', //1 = laisvas, 2 = rezervuota, 3 = parduota
        'plotas'        => '6.52',         
        'koordinacijos' => 'M506 32L554 8L583 17L537 43'
    ),
    array (
        'adresas' => 'razetų 9',
        'statusas'  => '1', //1 = laisvas, 2 = rezervuota, 3 = parduota
        'plotas'        => '6.58',         
        'koordinacijos' => 'M555 40L589 20L633 33L599 52'
    ),
    array (
        'adresas' => 'razetų 7',
        'statusas'  => '1', //1 = laisvas, 2 = rezervuota, 3 = parduota
        'plotas'        => '6.75',         
        'koordinacijos' => 'M605 55L639 35L688 49L652 69'
    )
);

$i = 0;
    foreach ($sklypas['items'] as $item => $value) { ?>
<g>
    <path 
    data-tippy-content='
    <strong>Nr: <?php echo ++$i;?> <br> 
    Adresas: <span class="capitalize"> <?php echo $value['adresas'];?> </span> <br> 
    Plotas: <?php echo $value['plotas'];?>a <br> 
    Statusas: 
    <?php if($value['statusas'] == '1') { ?>
       <span class="green"> Laisvas </span>
    <?php } ?>
    <?php if($value['statusas'] == '2') { ?>
       <span class="orange"> Rezervuota </span>
    <?php } ?>
    <?php if($value['statusas'] == '3') { ?>
       <span class="red"> Parduota </span>
    <?php } ?>
    <?php if($value['statusas'] == '1') { ?>
    <br> 
        <a href="<?php echo $domain;?><?php echo $url["quote_form"][0]?>?selectlist_253772=<?php $arr = array(" " => "-","ž" => "z","ų" => "u");echo strtr(ucfirst($value['adresas']), $arr);?>">
            Siūsti užklausą
        </a>
    </strong>
    <?php } ?>' 
    <?php if($value['statusas'] == '1') { ?>
        class="shp0" 
    <?php } ?>
    <?php if($value['statusas'] == '2') { ?>
        class="shp1" 
    <?php } ?>
    <?php if($value['statusas'] == '3') { ?>
        class="shp2" 
    <?php } ?>    
    d="<?php echo $value['koordinacijos'];?>" />
</g>
<?php } ?>
```
###### my few works I have done 
[landscaping company](https://mk-landscapes.com/)
[wheel repair](https://www.ratlankiutvarkymas.lt/)
[builders/brokers] (https://naujiejiginduliai.lt/)

###### Education - multimedia and communications in Aarhus business academy
###### I have passed IELC exam in 2009 with 6.5 score, studied in Denmark for 4 years and live ind UK for 4 years
