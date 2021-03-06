<h6 class="is-uppercase has-text-grey">Component</h6><h1 class="title is-1 is-family-secondary">Tabs</h1>
<hr class="is-visible is-size-3">
<p class="subtitle is-5 is-family-secondary">
    <span class="has-text-weight-semibold">Tabs</span> are used to quickly navigate between views within the same context.
</p>
<hr class="is-visible is-size-3"><br>

<div class="box has-background-white-bis is-marginless is-large">
    <div class="tabs">
        <ul>
            <li><a>Pilot</a></li>
            <li><a>Care</a></li>
            <li><a>Claim</a></li>
            <li class="is-active"><a>Full Package</a></li>
        </ul>
    </div>
</div>

    <div class="tabs">
        <ul>
            <li><a>Pilot</a></li>
            <li class="is-active"><a>Care</a></li>
            <li><a>Claim</a></li>
            <li><a>Full Package</a></li>
        </ul>
    </div>
<hr class="is-visible is-size-1">

<h2 class="title is-3 is-family-sans-serif">Hanging Tabs</h2>

Hanging Tabs have their active line placed above each item.

<br>

<div class="box has-background-white-bis is-marginless is-medium" style="padding-top: 0;">
    <div class="tabs is-hanging">
        <ul class="is-borderless">
            <li><a>These</a></li>
            <li><a>Are</a></li>
            <li class="is-active"><a>Hanging</a></li>
            <li><a>Tabs</a></li>
            <li>
                <a class="dropdown is-hoverable is-iconless has-arrow">
                    <div class="dropdown-trigger">•••</div>
                    <div class="dropdown-menu is-paddingless">
                        <div class="box is-white is-floating">Hey!<br><span class="is-size-7 has-text-grey">Just to show you can also<br>put sub-menus here 😉</span></div>
                    </div>
                </a>
            </li>
        </ul>
    </div>
</div>

    <div class="tabs is-hanging">
        <ul class="is-borderless">
            <li><a>Pilot</a></li>
            <li class="is-active"><a>Care</a></li>
            <li><a>Plan</a></li>
            <li><a>Claim</a></li>
        </ul>
    </div>
<br>

?> You can also remove the tabs line by adding `is-borderless` to the ul tag.

<hr class="is-visible is-size-1">

<h2 class="title is-3 is-family-sans-serif">Toggle Tabs</h2>

Make your Tabs acts as Togglers between different states (or tabs) by combining `is-toggle` with `is-fullwidth` classes.

<br><br>

<div class="box has-background-white-bis is-large is-marginless">
    <div class="tabs is-toggle is-fullwidth is-toggle-rounded">
        <ul>
            <li class="is-active"><a>Insured</a>
            </li><li><a>Employer</a></li>
            <li><a>Incapacity</a></li>
        </ul>
    </div>
</div>

    <div class="tabs is-boxed is-marginless">
        <ul class="is-borderless">
            <li><a>Employer</a></li>
            <li class="is-active"><a>Insured</a></li>
            <li><a>Incapacity</a></li>
            <li><a>Certificates</a></li>
        </ul>
    </div>
    <div class="box is-white is-floating">
        ...
    </div>

<hr>
<h3 class="title is-4">Make it move!</h3>

Animate the tab selector by adding `has-hr` and an `<hr>` tag after the last `<li></li>`.

<br>

<div class="box has-background-white-bis is-large is-marginless">
    <div class="tabs is-toggle is-fullwidth has-hr">
        <ul>
            <li id="js-tab-1" class="is-active"><a onclick="toggleTab(1)">Option A</a></li>
            <li id="js-tab-2" class=""><a onclick="toggleTab(2)">Option B</a></li>
            <li id="js-tab-3" class=""><a onclick="toggleTab(3)">Option C</a></li>
            <hr>
        </ul>
    </div>
    <hr>
    <div class="tabs is-toggle is-fullwidth has-hr is-small is-toggle-rounded">
        <ul>
            <li id="js-tab-4" class="is-active"><a onclick="toggleTab(4)">Option A</a></li>
            <li id="js-tab-5" class=""><a onclick="toggleTab(5)">Option B</a></li>
            <li id="js-tab-6" class=""><a onclick="toggleTab(6)">Option C</a></li>
            <hr>
        </ul>
    </div>
</div>

    <div class="tabs is-toggle is-fullwidth has-hr">
        <ul>
            <li class="is-active"><a>Option A</a></li>
            <li><a>Option B</a></li>
            <li><a>Option C</a></li>
            
            <hr> <!-- Don't forget that <hr> -->
        </ul>
    </div>
    
    <div class="tabs is-toggle is-fullwidth has-hr is-small is-toggle-rounded">
        <ul>
            <li><a> A </a></li>
            <li><a> B </a></li>
            <li><a> C </a></li>
            <hr>
        </ul>
    </div>

<hr class="is-visible is-size-1">

<h2 class="title is-3 is-family-sans-serif">Boxed Tabs</h2>

Give your Tabs a bolder look by using `is-boxed` in combinaision with a box component immediately after.

<br><br>

<div class="box has-background-white-bis is-large is-marginless">
    <div class="tabs is-boxed is-marginless is-centered">
        <ul class="is-borderless">
            <li class="is-active"><a>Insured</a>
            </li><li><a>Employer</a></li>
            <li><a>Incapacity</a></li>
            <li><a>Certificates</a></li>
        </ul>
    </div>
    <div class="box is-white is-large is-bordered has-text-grey-dark">
        Boxed content<br><i>Use Javascript for the tab switching behaviour.</i>
    </div>
</div>

    <div class="tabs is-boxed is-marginless">
        <ul class="is-borderless">
            <li><a>Employer</a></li>
            <li class="is-active"><a>Insured</a></li>
            <li><a>Incapacity</a></li>
            <li><a>Certificates</a></li>
        </ul>
    </div>
    <div class="box is-white is-floating">
        ...
    </div>
