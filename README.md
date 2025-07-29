# sgticketmaster
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>TicketClone</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background-color: #f5f5f5;
      color: #222;
    }

    .country-banner {
      background-color: #007bff;
      color: white;
      text-align: center;
      padding: 8px 15px;
      font-size: 0.9rem;
    }

    header {
      background-color: #1a1a1a;
      color: white;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    nav {
      display: flex;
      align-items: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      font-weight: bold;
    }

    .profile-dropdown {
      position: relative;
      display: inline-block;
    }

    .profile-btn {
      color: white;
      background: none;
      border: none;
      font-weight: bold;
      cursor: pointer;
      margin-left: 20px;
    }

    .dropdown-content {
      display: none;
      position: absolute;
      right: 0;
      background-color: white;
      min-width: 180px;
      box-shadow: 0px 8px 16px rgba(0,0,0,0.2);
      z-index: 1;
      border-radius: 5px;
      overflow: hidden;
    }

    .dropdown-content p {
      color: #222;
      padding: 12px 16px;
      margin: 0;
      font-size: 0.9rem;
      border-bottom: 1px solid #eee;
    }

    .profile-dropdown:hover .dropdown-content {
      display: block;
    }

    .hero {
      background: #001f3f;
      color: white;
      padding: 60px 30px;
      text-align: center;
    }

    .search-bar {
      margin-top: 20px;
    }

    .search-bar input {
      padding: 10px;
      width: 300px;
      max-width: 90%;
      border: none;
      border-radius: 4px;
    }

    .events-section {
      padding: 40px 30px;
    }

    .events-section h2 {
      margin-bottom: 20px;
      font-size: 1.6rem;
    }

    .event-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .event-card {
      background-color: white;
      border-radius: 8px;
      padding: 15px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .event-card h3 {
      font-size: 1.1rem;
      margin-bottom: 10px;
    }

    .event-card p {
      font-size: 0.9rem;
      color: #555;
    }

    footer {
      background-color: #1a1a1a;
      color: white;
      padding: 30px;
      text-align: center;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <div class="country-banner">
    You're browsing events in <strong>Singapore</strong>
  </div>

  <header>
    <div class="logo">
      <h1>TicketClone</h1>
    </div>
    <nav>
      <a href="#">Concerts</a>
      <a href="#">Sports</a>
      <a href="#">Arts & Theatre</a>
      <a href="#">More</a>

      <div class="profile-dropdown">
        <button class="profile-btn">Profile</button>
        <div class="dropdown-content">
          <p>Signed in as</p>
          <p><strong>Natasya Chua</strong></p>
        </div>
      </div>
    </nav>
  </header>

  <section class="hero">
    <h2>Discover Events Near You</h2>
    <div class="search-bar">
      <input type="text" placeholder="Search by artist, event, or venue">
    </div>
  </section>

  <section class="events-section">
    <h2>Popular Events</h2>
    <div class="event-grid">
      <div class="event-card">
        <h3>Maroon 5 Live in Singapore</h3>
        <p>Singapore Indoor Stadium • Sep 12, 2025</p>
      </div>
      <div class="event-card">
        <h3>Singapore Grand Prix 2025</h3>
        <p>Marina Bay Circuit • Sep 21, 2025</p>
      </div>
      <div class="event-card">
        <h3>Hamilton: The Musical</h3>
        <p>Esplanade Theatre • Aug 30, 2025</p>
      </div>
      <div class="event-card">
        <h3>Ed Sheeran Asia Tour</h3>
        <p>Singapore • Oct 14, 2025</p>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 TicketClone. All rights reserved.</p>
  </footer>

</body>
</html>
