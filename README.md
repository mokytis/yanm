# yanm: yet another network manager

**WARNING**: yanm is currently _very_ early alpha. In fact, as I write this,
there is currently no code that has been written, and the concept for how I want
to structure the project is still forming. Use it at your own risk. This notice
will be updated as the project's usability changes.

---

## The Idea

yanm is a network manager. That means that it takes responsibility for ensuring
that your network configuration (IPv4 and IPv6 addresses, gateways, DNS servers,
DNS search domains, etc.) are up to date whenever you change networks. I also
plan on giving yanm the power to handle other useful tasks like managing
wireguard connections.

## License

    yanm - a network manager for GNU/Linux systems
    Copyright (C) 2021  Luke Spademan <info@lukespademan.com>

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.
