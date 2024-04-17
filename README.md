<link rel="stylesheet" href="https://script.github.com/wealthbestlotto/assets/global/css/iziToast.min.css">
<script src="https://script.github.com/wealthbestlotto/assets/global/js/iziToast.min.js"></script>
            <script>
            "use strict";
            iziToast.warning({message:"You can not change anything over this demo", position: "topRight"});
        </script>
            <script>
            "use strict";
            iziToast.info({message:"This version is for demonstration purposes only and few actions are blocked", position: "topRight"});
        </script>
    
<script>
    "use strict";
    function notify(status,message) {
        iziToast[status]({
            message: message,
            position: "topRight"
        });
    }
</script>


<script src="https://script.github.com/wealthbestlotto/assets/admin/js/nicEdit.js"></script>

<script src="https://script.github.com/wealthbestlotto/assets/admin/js/vendor/select2.min.js"></script>
<script src="https://script.github.com/wealthbestlotto/assets/admin/js/app.js"></script>


<script>
    "use strict";
    bkLib.onDomLoaded(function() {
        $( ".nicEdit" ).each(function( index ) {
            $(this).attr("id","nicEditor"+index);
            new nicEditor({fullPanel : true}).panelInstance('nicEditor'+index,{hasPanel : true});
        });
    });
    (function($){
        $( document ).on('mouseover ', '.nicEdit-main,.nicEdit-panelContain',function(){
            $('.nicEdit-main').focus();
        });
    })(jQuery);
</script>

    <script>
        if ($('li').hasClass('active')) {
            $('#sidebar__menuWrapper').animate({
                scrollTop: eval($(".active").offset().top - 320)
            }, 500);
        }
    </script>


</body>
