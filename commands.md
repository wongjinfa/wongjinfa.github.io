git pull
> to update the page

#paste under <head> at the most bottom just before </head>

<link rel="stylesheet" href="../main-assets/main.css" type="text/css">
<script type="text/javascript" src="../assets/inserthtml.js"></script>

#paste under <body>

<div id="js-fixed-header-offset" style="margin-top: 0px;">
    <div w3-include-html="../inserts/header.html"></div>

        <div class="ws-theme-body">
            <div class="ws-theme-container">
                <div class="ws-theme-body-inner">
                    <div w3-include-html="../inserts/nav.html"></div>
                    <main class="ws-theme-content" role="main">
                        <div class="ws-theme-content-inner">
                            <div class="contentBox">
                                <div class="innerContentBox" id="WikiContent">

                                </div>
                            </div>
                        </div>
                    </main>
                </div>
            </div>
        </div>
    </div>
</div>

#at the bottom just before </body>

<script>
    includeHTML()
</script>