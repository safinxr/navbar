## navbar
import { Link, NavLink } from 'react-router-dom';

<nav className="navbar navbar-expand-lg navbar-light shadow-lg sticky-top">
    <div className="container">
      <Link className='navbar-brand' to='/'>
        <img width={100} src="https://www.thebalancesmb.com/thmb/Up42pSsoj8P6CxHrpppq0y9cX9w=/754x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/DesignEvo-6f330ebd82a94aebad9e1546cf6bf992.png" alt="" />
      </Link>
      <button className="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span className="navbar-toggler-icon"></span>
      </button>
      <div className="collapse navbar-collapse" id="navbarSupportedContent">
        <ul className="navbar-nav ms-auto">
          <li className='nave-item'>
            <NavLink
              className={({ isActive }) =>
                isActive ? "nav-link text-info fs-5" : "nav-link fs-5"
              }
              to="/"
            >
              Home
            </NavLink>
          </li>
          <li className='nave-item'>
            <NavLink
              className={({ isActive }) =>
                isActive ? "nav-link text-info fs-5" : "nav-link fs-5"
              }
              to="/about"
            >
              About
            </NavLink>
          </li>
          <li className='nave-item'>
            <NavLink
              className={({ isActive }) =>
                isActive ? "nav-link text-info fs-5" : "nav-link fs-5"
              }
              to="/login"
            >
              Login
            </NavLink>
          </li>
          <li className='nave-item'>
            <NavLink
              className={({ isActive }) =>
                isActive ? "nav-link text-info fs-5" : "nav-link fs-5"
              }
              to="/signup"
            >
              Signup
            </NavLink>
          </li>
        </ul>

      </div>
    </div>
  </nav>
