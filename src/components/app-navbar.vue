<template>
  <nav class="navbar navbar-expand-lg bg-pink  fixed-top" color-on-scroll="300">
    <div class="container">
      <div class="navbar-translate">
        <a class="navbar-brand" href="../index.html" rel="tooltip" title="Designed and Coded by Creative Tim" data-placement="bottom" target="_blank">
          <span>BLK•</span> Design System PRO
        </a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navigation" aria-controls="navigation-index" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-bar bar1"></span>
          <span class="navbar-toggler-bar bar2"></span>
          <span class="navbar-toggler-bar bar3"></span>
        </button>
      </div>
      <div class="collapse navbar-collapse" id="navigation">
        <div class="navbar-collapse-header">
          <div class="row">
            <div class="col-6 collapse-brand">
              <a>
                BLK•
                <span> PRO </span>
              </a>
            </div>
            <div class="col-6 collapse-close text-right">
              <button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navigation" aria-controls="navigation-index" aria-expanded="false" aria-label="Toggle navigation">
                <i class="tim-icons icon-simple-remove"></i>
              </button>
            </div>
          </div>
        </div>
        <ul class="navbar-nav ml-auto">
          <li class="dropdown nav-item">
            <a href="#" class="dropdown-toggle nav-link" data-toggle="dropdown">
              <i class="fa fa-cogs d-lg-none d-xl-none"></i> Getting started
            </a>
            <div class="dropdown-menu dropdown-with-icons">
              <a href="../index.html" class="dropdown-item">
                <i class="tim-icons icon-paper"></i> Components
              </a>
              <a href="../presentation.html" class="dropdown-item">
                <i class="tim-icons icon-bullet-list-67"></i>Presentation Page
              </a>
              <a href="../docs/1.0/getting-started/overview.html" class="dropdown-item">
                <i class="tim-icons icon-book-bookmark"></i>Documentation
              </a>
            </div>
          </li>
          <li class="nav-item dropdown">
            <a href="#" class="nav-link dropdown-toggle" id="navbarDropdownMenuLink" data-toggle="dropdown">
              <i class="tim-icons icon-paper" aria-hidden="true"></i>
              <p>Sections</p>
            </a>
            <div class="dropdown-menu dropdown-menu-right" aria-labelledby="navbarDropdownMenuLink">
              <a class="dropdown-item" href="../sections.html#headers">
                <i class="tim-icons icon-app"></i> Headers
              </a>
              <a class="dropdown-item" href="../sections.html#features">
                <i class="tim-icons icon-settings"></i> Features
              </a>
              <a class="dropdown-item" href="../sections.html#blogs">
                <i class="tim-icons icon-align-left-2"></i> Blogs
              </a>
              <a class="dropdown-item" href="../sections.html#teams">
                <i class="tim-icons icon-user-run"></i> Teams
              </a>
              <a class="dropdown-item" href="../sections.html#projects">
                <i class="tim-icons icon-paper"></i> Projects
              </a>
              <a class="dropdown-item" href="../sections.html#pricing">
                <i class="tim-icons icon-money-coins"></i> Pricing
              </a>
              <a class="dropdown-item" href="../sections.html#testimonials">
                <i class="tim-icons icon-chat-33"></i> Testimonials
              </a>
              <a class="dropdown-item" href="../sections.html#contactus">
                <i class="tim-icons icon-mobile"></i> Contact Us
              </a>
              <a class="dropdown-item" href="../sections.html#tables">
                <i class="tim-icons icon-chart-bar-32"></i> Tables
              </a>
              <a class="dropdown-item" href="../sections.html#accordion">
                <i class="tim-icons icon-paper"></i> Accordion
              </a>
            </div>
          </li>
          <li class="nav-item dropdown">
            <a href="#" class="nav-link dropdown-toggle" id="navbarDropdownMenuLink" data-toggle="dropdown">
              <i class="tim-icons icon-book-bookmark" aria-hidden="true"></i>
              <p>Examples</p>
            </a>
            <div class="dropdown-menu dropdown-menu-right" aria-labelledby="navbarDropdownMenuLink">
              <a class="dropdown-item" href="about-us.html">
                <i class="tim-icons icon-bulb-63"></i> About-us
              </a>
              <a class="dropdown-item" href="blog-post.html">
                <i class="tim-icons icon-align-center"></i> Blog Post
              </a>
              <a class="dropdown-item" href="blog-posts.html">
                <i class="tim-icons icon-chart-bar-32"></i> Blog Posts
              </a>
              <a class="dropdown-item" href="contact-us.html">
                <i class="tim-icons icon-square-pin"></i> Contact Us
              </a>
              <a class="dropdown-item" href="landing-page.html">
                <i class="tim-icons icon-paper"></i> Landing Page
              </a>
              <a class="dropdown-item" href="pricing.html">
                <i class="tim-icons icon-coins"></i> Pricing
              </a>
              <a class="dropdown-item" href="ecommerce.html">
                <i class="tim-icons icon-basket-simple"></i> Ecommerce Page
              </a>
              <a class="dropdown-item" href="product-page.html">
                <i class="tim-icons icon-bag-16"></i> Product Page
              </a>
              <a class="dropdown-item" href="profile-page.html">
                <i class="tim-icons icon-lock-circle"></i> Profile Page
              </a>
              <a class="dropdown-item" href="error.html">
                <i class="tim-icons icon-button-power"></i> 404 Error Page
              </a>
              <a class="dropdown-item" href="500-error.html">
                <i class="tim-icons icon-alert-circle-exc"></i> 500 Error Page
              </a>
              <a href="#" class="dropdown-item dropdown-toggle" id="navbarDropdown2" data-toggle="dropdown">
                <i class="tim-icons icon-book-bookmark" aria-hidden="true"></i> App Pages
              </a>
              <div class="dropdown-menu" aria-labelledby="navbarDropdown2">
                <a class="dropdown-item" href="account-settings.html">
                  <i class="tim-icons icon-lock-circle"></i> Account Settings
                </a>
                <a class="dropdown-item" href="login-page.html">
                  <i class="tim-icons icon-tablet-2"></i> Login Page
                </a>
                <a class="dropdown-item" href="register-page.html">
                  <i class="tim-icons icon-laptop"></i> Register Page
                </a>
                <a class="dropdown-item" href="reset-page.html">
                  <i class="tim-icons icon-molecule-40"></i> Reset Page
                </a>
                <a class="dropdown-item" href="invoice-page.html">
                  <i class="tim-icons icon-notes"></i> Invoice Page
                </a>
                <a class="dropdown-item" href="checkout-page.html">
                  <i class="tim-icons icon-basket-simple"></i> Checkout Page
                </a>
                <a class="dropdown-item" href="chat-page.html">
                  <i class="tim-icons icon-email-85"></i> Chat Page
                </a>
              </div>
            </div>
          </li>
          <li class="nav-item">
            <a class="nav-link btn btn-sm btn-default" href="https://www.creative-tim.com/product/blk-design-system-pro" target="_blank">
              <p>Buy Now</p>
            </a>
          </li>
          <!-- <li class="nav-item">
					<a class="nav-link" rel="tooltip" title="Follow us on Twitter" data-placement="bottom" href="https://twitter.com/CreativeTim" target="_blank">
						<i class="fab fa-twitter"></i>
						<p class="hidden-lg-up">Twitter</p>
					</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" rel="tooltip" title="Like us on Facebook" data-placement="bottom" href="https://www.facebook.com/CreativeTim" target="_blank">
						<i class="fab fa-facebook-square"></i>
						<p class="hidden-lg-up">Facebook</p>
					</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" rel="tooltip" title="Follow us on Instagram" data-placement="bottom" href="https://www.instagram.com/CreativeTimOfficial" target="_blank">
						<i class="fab fa-instagram"></i>
						<p class="hidden-lg-up">Instagram</p>
					</a>
				</li> -->
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
import {HTTP} from '@/common';
import notify from "@/components/notify"
import appnavbar from "@/components/app-navbar";
import appfooter from "@/components/app-footer";
  const submenu = [        
    {to:'/',icon:'',title:'Home'},        
    {to:'/about',icon:'',title:'About Us'},        
    {to:'/success',icon:'',title:'Success Stories'},        
    {to:'/contact',icon:'',title:'Contact Us'},        
  ]

export default {
	components: {notify, appnavbar, appfooter},
	data(){ return { formSignup:{Username:"x",Password:"x",Email:""}, notifications:[]}},
	methods: {
      signup() {
		const app = this;
		if (app.formSignup.Email !== "") {
			app.formSignup.Username = app.formSignup.Email;
			app.formSignup.Password = app.formSignup.Email;
		}
        HTTP.post('/api/signup', app.formSignup ,{withCredentials: true}).then(response => {
          console.log(response)
          app.notifications.push(response.data)
		  setTimeout(checkRedirect(response.data),1500)
          if (response.data.Code == 200) {
			  app.formSignup.Username = "x";
			  app.formSignup.Password = "x";
			  app.formSignup.Email = "";
		  }
        }).catch(e => {
          console.log(e)
          this.error = e
          // this.errors.push(e)
        })
      }
    }
}
</script>