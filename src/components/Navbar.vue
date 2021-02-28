 <template>
  <nav>
      <div class="nav-wrapper green">
        <div class="container">
          <router-link to="/" class="brand-logo center">Employee Manager</router-link>
                    <ul id="nav-mobile" class="left hide-on-med-and-down">
                        <li><router-link to="/">Dashboard</router-link></li>
                        <li><router-link to="/new">New Employee</router-link></li>
                    </ul>    
        </div>
      </div>
    </nav>
  </template>