* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Arial', sans-serif;
}

body {
  background: #f9f9f9;
  color: #333;
}

.navbar {
  background: #002244;
  color: white;
  padding: 15px 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 20px;
}

.nav-links li a {
  color: white;
  text-decoration: none;
}

.hero {
  background: url('https://source.unsplash.com/1600x600/?football') no-repeat center center/cover;
  height: 60vh;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  text-align: center;
}

.hero .btn {
  background: #ffaa00;
  color: black;
  padding: 10px 20px;
  text-decoration: none;
  font-weight: bold;
  margin-top: 10px;
  display: inline-block;
}

.predictions, .pricing, .contact {
  padding: 40px 20px;
  text-align: center;
}

.prediction-card, .pricing-plan {
  background: white;
  padding: 20px;
  margin: 15px auto;
  max-width: 400px;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

.pay-btn {
  background: #28a745;
  color: white;
  padding: 10px 15px;
  border: none;
  cursor: pointer;
  font-size: 16px;
  margin-top: 10px;
}

footer {
  text-align: center;
  background: #002244;
  color: white;
  padding: 15px 0;
}
