.navbar {
  opacity: 0.7;
}
.nav-menu ul {
  margin: 0;
  padding: 0;
  list-style: none;
}

.nav-menu > ul {
  display: flex;
}

.nav-menu > ul > li {
  position: relative;
  white-space: nowrap;
  padding: 10px 0 10px 28px;
}

.nav-menu a {
  display: block;
  position: relative;
  color: #222222;
  transition: 0.3s;
  font-size: 15px;
  font-weight: 600;
  padding: 0 3px;
  font-family: "Open Sans", sans-serif;
}

.nav-menu > ul > li > a:before {
  content: "";
  position: absolute;
  width: 100%;
  height: 2px;
  bottom: -5px;
  left: 0;
  background-color: #ff7300;
  visibility: hidden;
  width: 0px;
  transition: all 0.3s ease-in-out 0s;
}

.nav-menu a:hover:before, .nav-menu li:hover > a:before, .nav-menu .active > a:before {
  visibility: visible;
  width: 100%;
}
.card-jasa{
  min-height: 380px;
  background-color:rgb(51, 35, 35);
  color:#fff;
  padding:10px;
  background-size: cover;
  margin-bottom: 20px;
}
.jasa-button {
  background-color: violet;
}
.jasa-button:hover {
  background-color: rgb(248, 174, 248);
}
.contact {
    background-color: #f7f8fc;
}
.contact .info {
    padding: 30px;
    width: 100%;
    background: #fff;
    box-shadow: 0px 2px 15px rgba(0, 0, 0, 0.1);
  }
  
  .contact .info i {
    font-size: 20px;
    color: #1bac91;
    float: left;
    width: 44px;
    height: 44px;
    background: #88ccac;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 50px;
    transition: all 0.3s ease-in-out;
  } 
  .contact .info h4 {
    padding: 0 0 0 60px;
    font-size: 22px;
    font-weight: 600;
    margin-bottom: 5px;
    color: #21413c;
  } 
  .contact .info p {
    padding: 0 0 0 60px;
    margin-bottom: 0;
    font-size: 14px;
    color: #43857a;
  }  
  .contact .info .email p {
    padding-top: 5px;
  }  
  .contact .info .social-links {
    padding-left: 60px;
  }  
  .contact .info .social-links a {
    font-size: 18px;
    display: inline-block;
    background: #333;
    color: #fff;
    line-height: 1;
    padding: 8px 0;
    border-radius: 50%;
    text-align: center;
    width: 36px;
    height: 36px;
    transition: 0.3s;
    margin-right: 10px;
  }  
  .contact .info .social-links a:hover {
    background: #1bac91;
    color: #fff;
  }  
  .contact .info .email:hover i, .contact .info .address:hover i, .contact .info .phone:hover i {
    background: #1bac91;
    color: #fff;
  }
  section {
    padding: 60px 0;
    overflow: hidden;
  } 
  .section-bg {
    background-color: #f7f8fc;
  }
.section-title {
    padding-bottom: 40px;
    text-align: center;
  } 
  .section-title h2 {
    font-size: 36px;
    font-weight: 300;
    margin-bottom: 20px;
    padding-bottom: 0;
    color: #21413c;
  } 
  .section-title p {
    margin-bottom: 0;
  }
  .services .icon-box {
    padding: 30px;
    position: relative;
    overflow: hidden;
    margin: 0;
    background: #fff;
    transition: all 0.3s ease-in-out;
    border-radius: 30px;
    text-align: center;
    border-bottom: 3px solid #fff;
  }
  
  .services .icon-box:hover {
    box-shadow: 0 2px 29px 0 rgba(37, 37, 37, 0.1);
  }
  
  .services .icon i {
    font-size: 48px;
    line-height: 1;
    margin-bottom: 15px;
  }
  
  .services .title {
    font-weight: 700;
    margin-bottom: 15px;
    font-size: 18px;
  }
  .services .title a {
    color: #111;
  }
  
  .services .description {
    font-size: 15px;
    line-height: 28px;
    margin-bottom: 0;
  }
footer {
    background-color: #08202c;
}
